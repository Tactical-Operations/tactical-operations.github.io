## WIP - Logistikbestellkatalog

<style>
.logistic-table-order-catalog { 
  table tbody tr:nth-child(1) { background-color: var(--logistic-table-infantry-color); }
  table tbody tr:nth-child(2) { background-color: var(--logistic-table-medic-color);}
  table tbody tr:nth-child(3) { background-color: var(--logistic-table-medic-only-color);  }
  table tbody tr:nth-child(4) { background-color: var(--logistic-table-logistic-only-color);  }
  table tbody tr:nth-child(5) { background-color: var(--logistic-table-vehicle-color);  }
  table tbody tr:nth-child(6) { background-color: var(--logistic-table-lead-color);  }
  table tbody tr:nth-child(7) { background-color: var(--logistic-table-air-color);  }
}
</style>

<div markdown="1" class="logistic-table logistic-table-2 logistic-table-order-catalog">

| Farbe | Einheitengattung |
| :-----: | :-----: |
| **Grün** | **Für Infanterie** |
| **Rosa** | **Medizinisch (für alle)** |
| **Rot** | **Für medizinisches Personal** |
| **Gelb** | **Exkl. für Logistiker** |
| **Orange** | **Fahrzeugwartung** |
| **Lila-Blau** | **Für Führungskräfte** |
| **Blau** | **Für Luftstreitkräfte** |

</div>

<div markdown="1" class="hidden">

#### Supply Units

<style>
.logistic-table-supply-units { 
  table tbody tr { background-color: var(--logistic-table-infantry-color); }
  table tbody tr:nth-child(2) { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(3) { background-color: var(--logistic-table-vehicle-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-supply-units">

| Nr | Supply Units | Beschreibung/Inhalt |
| :---: | :---- | :---- |
| 0-01 | **Platoon Supply Unit**  | 4x Infanteriemunition (pro Squad)<br> 2x Granaten (inkl. für Granatwerfer)<br> 1x Medizinische Vorräte (Pro Platoon/Infanterie)<br> 1x Panzerabwehr |
| 0-02  | **Vehicle Supply Unit**  | Fahrzeugmunition-Palette/-Box Treibstoff-Palette Betankung und Aufmunitionierung durch Logistiker/Combat Engineer |
| 0-03 | **Vehicle Repair Unit**   | Fahrzeugreparatur-Palette Ersatzreifen (in Box) Reparatur durch Logistiker/Combat Engineer |

</div>

#### Infanterieversorgung

<style>
.logistic-table-infantry-supply {
  table tbody tr { background-color: var(--logistic-table-infantry-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-infantry-supply">

| Nr | Infanterieversorgung | Beschreibung/Inhalt |
| :---: | :---- | :---- |
| 1-01 | Infanteriemunition (Pro Squad) | Gewehrmunition für alle Infanterierollen |
| 1-02 | Panzerabwehr | 2x M136 (HEAT), 3x Javelin-Rakete, 3x SMAW Raketen |
| 1-02 | Flugabwehr | 2x FIM-92 Stinger Werfer, 6x FIM-92-Raketen |
| 1-03 | Granaten (inkl. für Granatwerfer) | Explosiv-& Rauchgranaten (inkl. 40mm) |
| 1-04 | Nachtkampf-Ausstattung | NVGs, Flares (inkl. 40mm), Knicklichter, IR-Stroboskope |
| 1-05 | Minen-Kiste | 2x Minensucher, 20x APERS Minenwerfer, 20x Panzerabwehrminen, 20x M4A1 SLAM, Stolperdraht-Leuchtrakete |
| 1-06 | Pionierkiste | 5x Minensucher, 5x Entschärfungs-Kit, 5x IED Notebook, 40x TNT Charge (75g) |
| 1-07 | Führungskiste | Spezialkiste mit Tablets, Tabs, Rauchgranaten und Lasermarkierer |
| 1-08 | Marine Raider-Versorgung | Munitionskiste exklusiv für die Bewaffnung der Marine Raider |
| 1-09 | Medizinische Vorräte (Pro Platoon/Infanterie) | Kiste mit Sanitätsmaterial, das ein gesamtes Platoon versorgen sollte |
| 1-10 | Logistiker-Versorgung | Kiste mit Werkzeugen der Logistik |
| 1-11 | UAV-Kiste | 20x UAV-Batterie \+ 1x UAV-Terminal |
| 1-12 | (ACE) Sanitätskiste (Standard) | Exkl. für Dustoff 9-1 |
| 1-13 | (KAM) Allgemeine Gegenstände | Exkl. für Dustoff 9-1 |
| 1-14 | (ACE) Sanitätskiste (Erweitert) | Exkl. für Dustoff 9-1 |
| 1-15 | (KAM) Medikamentenkiste | Exkl. für Dustoff 9-1 |
| 1-16 | (KAM) Medizinische Blutbank | Exkl. für Dustoff 9-1 |
| 1-69 | Kleine Kiste (leer)/Große Kiste (leer) | Dient für Sonderbestellungen |

</div>

#### Fahrzeugversorgung

<style>
.logistic-table-vehicle-supply {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-vehicle-supply">

| Nr | Fahrzeugversorgung | Beschreibung/Inhalt |
| :---: | :---- | :---- |
| 2-01 | Ersatzreifen | Bei mehr als einem Ersatzreifen bitte **2-08** anfordern. |
| 2-02 | Ersatzkette |  |
| 2-03 | Fahrzeugmunition-Palette Oder Fahrzeugmunition-Box | Frachtpalette, um Fahrzeuge aufzumunitionieren oder die Pylonen zu ändern |
| 2-04 | Fahrzeugreparatur-Palette | Frachtpalette, um Fahrzeuge komplett zu reparieren |
| 2-05 | Treibstoff-Palette | Frachtpalette, um Fahrzeuge aufzutanken (3406l) |
| 2-06 | Seahawk Hoist | Seilwinde, die an Seahawk-Modellen montiert werden kann. |
| 2-07 | Ersatzreifen (in Box) | Frachtkiste, vorgefüllt mit 20 Ersatzreifen |

</div>


#### Schwere Waffen/Artillerie

<style>
.logistic-table-artillery-supply {
  table tbody tr { background-color: var(--logistic-table-lead-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-artillery-supply">

| Nr | Schwere Waffen/Artillerie | Beschreibung/Inhalt |
| :---: | :---- | :---- |
| 3-01 | M2HB (Verpackt) | HMG auf Dreibein montiert, wird stehend bedient |
| 3-02 | M2-Munition | 10x Gurte mit Leuchtspur (rot) |
| 3-03 | MK19 (Verpackt) | GMW auf Dreibein montiert, wird sitzend bedient |
| 3-04 | MK19-Munition | 12x HE, 4x HEDP, 8x Kanister |
| 3-05 | M41A4 TOW (Verpackt) | Statische AT auf Dreibein montiert, wird kniend bedient |
| 3-06 | TOW-Munition | 2x BGM-71E TOW-2A (Fahrzeugbekämpfung) 3x BGM-71H Bunker Buster (Bekämpfung von Stellungen und Infanterie) |
| 3-07 | FIM-92 Stinger - Plattform | Statische Luftabwehrstation, nicht Radar-gestützt |

</div>

#### Landfahrzeuge

<style>
.logistic-table-land-vehicle {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-land-vehicle">

| Nr | Landfahrzeuge | Sitzplätze | Anmerkungen |
| :---: | :---- | :-----: | :---- |
| 4-01 | AAVP-7A1 | 21 |  |
| 4-02 | LAV-25 | 9 |  |
| 4-03 | LAV-C2 | 4 | Fahrzeug für Kompanieführung und Lizard 1-1|
| 4-05 | HUMVEE | 4 |  |
| 4-06 | HUMVEE (M2) | 5 |  |
| 4-07 | HUMVEE (TOW) | 5 |  |
| 4-8 | HUMVEE (SAG-2/M2/M240) | 15 |  |
| 4-9 | LKW (Infanterie) | 15 |  |
| 4-10 | Buggy | 6 |  |

</div>

#### Luftfahrzeuge

<style>
.logistic-table-air-vehicle {
  table tbody tr { background-color: var(--logistic-table-air-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-air-vehicle">

| Nr | Luftfahrzeuge | Sitzplätze | Zweck/Nutzen |
| :---: | :---- | :-----: | :---- |
| 5-01 | UH-1Y Venom | 17 | Infanterietransport |
| 5-02 | MH-60S Seahawk (Medevac/Logistik) | 18 | Patienten-/Frachttransport |
| 5-03 | CH-53E (GAU-21) | 27 | Fracht-/Infanterietransport |
| 5-04 | AH-1Z Viper | 2 | CAS |
| 5-05 | MV-22 Osprey (M134+M2) | 26 | Infanterietransport |
| 5-06 | F/A-18C | 1 | Luftüberlegenheitsjäger |

</div>

#### Wasserfahrzeuge

<style>
.logistic-table-sea-vehicle {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-sea-vehicle">

| Nr | Wasserfahrzeuge | Sitzplätze | Beschreibung/Inhalt |
| :---: | :---- | :-----: | ----- |
| 6-01 | Schnellboot Minigun | 11 | Kampfboot mit GMW und 7.62 Minigun |
| 6-02 | MK.V SOC | 33 | Patroullienboot  |
| 6-03 | RHIB | 8 | Unbewaffnetes Boot |

</div>

#### Bauvorhaben/Stellungen

<style>
.logistic-table-construction {
  table tbody tr { background-color: var(--logistic-table-logistic-only-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-construction">

| Nr | Bauvorhaben/Stellungen\* | Bauzeit\* | Beschreibung |
| :---: | :---- | :-----: | :---- |
| 7-01 | Munitionsversteck | \~ 15 Min | Kleines verstecktes Lager für Infanterie Versorgung |
| 7-02 | Versorgungspunkt(Für die Frontversorgung) | \~ 30 Min | Kleine Stellung nahe der Front, meist an Straße |
| 7-03 | \+ Integration von 1-2 Helipads | \~ 15 Min | Inkl. Versorgung für Helis |
| 7-04 | \+ Integration eines Feldlazaretts | \~ 15 Min  | Medizinisches Gebäude |
| 7-05 | Kleine FOB | \~ 120 Min | Beinhaltet 7-03, 7-04 und ein Lager für Ersatzfahrzeuge |
| 7-06 | Minenfeld AP je 100m | \~ 30 Min | Linie, wird ausgelegt mit Minenwerfern |
| 7-07 | Minenfeld AT je 50m | \~ 30 Min |  Zick-Zack Muster? |
| 7-08 | Kleine Fire Support Base | \~ 60 Min | Bunkerstellung mit mehreren schweren Waffen |
| 7-09 | Flexible Bauvorhaben | Variabel | Stacheldraht-Konstruktionen, Stellungen, Fahrzeugsperren, Aufbau von Fallen, Brückenbau |

</div>

\*= Die Bauzeiten sind pragmatisch eingeschätzt und werden voraussichtlich kürzer sein.

#### Wartung Luftfahrzeuge

<style>
.logistic-table-air-vehicle-maintenance {
  table tbody tr { background-color: var(--logistic-table-air-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-air-vehicle-maintenance">

| Nr | Wartung Luftfahrzeuge | Beschreibung/Inhalt |
| :--- | :---- | :---- |
| 8-01 | Reparatur |  |
| 8-02 | Betankung |  |
| 8-03 | Aufmunitionieren |  |
| 8-04 | Pylonenwechsel | Neu-Bestückung von Pylonen |
| 8-05 | Umbau von Blackhawk | Installation eines **2-06** an Blackhawk oder Entfernung von Türen von Blackhawk |

</div>

#### Sonstiges


<style>
.logistic-table-others {
  table tbody tr { background-color: var(--logistic-table-lead-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-3 logistic-table-others">

| Nr | Sonstiges | Beschreibung/Inhalt |
| :--- | :---- | :---- |
| 9-01 | Überführen/Transport eines Fahrzeugs | Falls Fahrzeuge in die Basis zurück oder zu einer nachverlegt werden müssen aufgrund eines Lufttransports |
| 9-02 | Minenräum-Kommando | Falls Minenfelder geräumt werden sollen. |
| 9-03 | Wracks bergen | Logistiker formen ein Bergungs-Kommando, um ein Wrack zu bergen. |
| 9-04 | Sonderauftrag | Inhalt wird mit Logistikleitung besprochen und festgelegt, sofern Kapazitäten vorhanden sind. |

</div>

</div>
