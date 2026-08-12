## Logistikinventar

Das Logistikinventar dokumentiert die verfügbaren Fahrzeuge und Systeme. Begrenzte Bestände gelten jeweils
**pro Mission**: Jede Mission beginnt mit dem aufgeführten Anfangsbestand. Verlorene oder zerstörte Fahrzeuge
reduzieren den verfügbaren Bestand nur innerhalb der laufenden Mission.

#### Begrenzter Gesamtbestand

<style>
.logistic-table-logistic-inventory {
  table tbody tr:nth-child(-n+3) { background-color: var(--logistic-table-air-color); }
  table tbody tr:nth-child(n+4):nth-child(-n+6) { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(n+7):nth-child(-n+8) { background-color: var(--logistic-table-air-color); }
  table tbody tr:nth-child(n+9):nth-child(-n+15) { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(n+16) { background-color: var(--logistic-table-logistic-only-color); }
}
.logistic-table-inventory-unlimited {
  table tbody tr:nth-child(1) { background-color: var(--logistic-table-air-color); }
  table tbody tr:nth-child(2) { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(n+3) { background-color: var(--logistic-table-logistic-only-color); }
}
.logistic-table-inventory-ground,
.logistic-table-inventory-sea {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
}
.logistic-table-inventory-air {
  table tbody tr { background-color: var(--logistic-table-air-color); }
}
.logistic-table-inventory-logistic {
  table tbody tr { background-color: var(--logistic-table-logistic-only-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-logistic-inventory">

| Kategorie | Fahrzeug/System | Initialer Bestand pro Mission |
|:----------|:----------------|-------------------------------:|
| Luftfahrzeuge | AH-1Z Viper | 4 |
| Luftfahrzeuge | MH-60M DAP MLASS | 3 |
| Luftfahrzeuge | UH-1Y Venom Gunship | 4 |
| Panzerfahrzeuge | AAVP-7A1 (Amtrack) | 6 |
| Panzerfahrzeuge | LAV-25 | 6 |
| Panzerfahrzeuge | LAV-C2 | 3 |
| SAM | AN/MPQ-105 Radar | 1 |
| SAM | MIM-104 Patriot | 1 |
| Radfahrzeuge | Buggy | 4 |
| Radfahrzeuge | HUMVEE (M2) | 4 |
| Radfahrzeuge | HUMVEE (TOW) | 2 |
| Radfahrzeuge | LKW (Infanterie) | 8 |
| Boote | MK.V SOC | 2 |
| Boote | RHIB | 20 |
| Boote | Schnellboot Minigun | 4 |
| Logistikfahrzeuge | HUMVEE Cargo | 4 |
| Logistikfahrzeuge | LKW (Cargo) | 6 |
| Logistikfahrzeuge | LKW (Fuel) | 4 |
| Logistik-Luftfahrzeuge | CH-53E (Cargo) | 2 |
| Logistik-Luftfahrzeuge | CH-53E (GAU-21) | 2 |
| Logistik-Luftfahrzeuge | UH-60M Slick (Cargo) | 2 |

</div>

#### Unbegrenzter Bestand

Die folgenden Fahrzeuge und Geräte sind im Inventory nicht mengenbegrenzt:

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-inventory-unlimited">

| Kategorie | Fahrzeug/Gerät |
|:----------|:-----------------|
| Luftfahrzeuge | F/A-18C Hornet |
| Boote | Schlauchboot |
| Logistikfahrzeuge | Gabelstapler |
| Logistikfahrzeuge | Gabelstapler (Atlas) |
| Logistikfahrzeuge | Quadbike (VHF-30108) |
| Logistikfahrzeuge | Traktor |

</div>

#### Fahrzeug- und Transportkapazitäten

Die **Besatzungsplätze** umfassen alle Plätze, die zur Bedienung des Fahrzeugs vorgesehen sind, beispielsweise
Fahrer, Pilot, Kommandant und Waffenschützen. **Mitfahrer-/Passagierplätze** sind die darüber hinaus verfügbaren
Plätze. Für die Transportplanung müssen Besatzungsplätze und Passagierplätze daher getrennt betrachtet werden.

#### Landfahrzeuge

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-inventory-ground">

| Fahrzeug | Besatzungsplätze | Mitfahrer-/Passagierplätze | Gesamtplätze |
|:---------|------------------:|------------------------------:|-------------:|
| AAVP-7A1 Amtrack | 3 | 12 | 15 |
| LAV-25 | 3 | 6 | 9 |
| LAV-C2 (Command) | 3 | 3 | 6 |
| HUMVEE (M2) | 2 | 3 | 5 |
| HUMVEE (TOW) | 2 | 3 | 5 |
| LKW (Infanterie) | 1 | 11 | 12 |
| Buggy | 1 | 5 | 6 |

</div>

#### Logistikfahrzeuge und Geräte

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-inventory-logistic">

| Fahrzeug/Gerät | Besatzungsplätze | Mitfahrer-/Passagierplätze | Gesamtplätze |
|:-----------------|------------------:|------------------------------:|-------------:|
| Gabelstapler | 1 | 0 | 1 |
| Gabelstapler (Atlas) | 1 | 0 | 1 |
| HUMVEE Cargo | 1 | 1 | 2 |
| LKW (Cargo) | 1 | 1 | 2 |
| LKW (Fuel) | 1 | 1 | 2 |
| Quadbike (VHF-30108) | 1 | 1 | 2 |
| Traktor | 1 | 0 | 1 |

</div>

#### Luftfahrzeuge

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-inventory-air">

| Luftfahrzeug | Besatzungsplätze | Mitfahrer-/Passagierplätze | Gesamtplätze |
|:-------------|------------------:|------------------------------:|-------------:|
| UH-1Y Venom Gunship | 4 | 1 | 5 |
| AH-1Z Viper | 2 | 0 | 2 |
| MH-60M DAP MLASS | 4 | 10 | 14 |
| UH-60M Slick (Cargo) | 4 | 4 | 8 |
| CH-53E (Cargo) | 2 | 0 | 2 |
| CH-53E (GAU-21) | 3 | 24 | 27 |
| F/A-18C Hornet | 1 | 0 | 1 |

</div>

#### Wasserfahrzeuge

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-inventory-sea">

| Wasserfahrzeug | Besatzungsplätze | Mitfahrer-/Passagierplätze | Gesamtplätze |
|:---------------|------------------:|------------------------------:|-------------:|
| Schnellboot Minigun | 3 | 8 | 11 |
| RHIB | 1 | 7 | 8 |
| Schlauchboot | 1 | 4 | 5 |
| MK.V SOC | 7 | 26 | 33 |

</div>

AN/MPQ-105 Radar und MIM-104 Patriot sind SAM-Systeme ohne Personen- oder Transportplätze.
