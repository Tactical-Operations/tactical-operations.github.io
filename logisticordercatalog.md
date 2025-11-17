## Logistikbestellkatalog

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

|     Farbe     |        Einheitengattung        |
|:-------------:|:------------------------------:|
|   **Grün**    |       **Für Infanterie**       |
|   **Rosa**    |   **Medizinisch (für alle)**   |
|    **Rot**    | **Für medizinisches Personal** |
|   **Gelb**    |    **Exkl. für Logistiker**    |
|  **Orange**   |  **Für Fahrzeuge + Wartung**   |
| **Lila-Blau** |     **Für Führungskräfte**     |
|   **Blau**    |    **Für Luftstreitkräfte**    |

</div>

#### Supply Units

<style>
.logistic-table-supply-units { 
  table tbody tr { background-color: var(--logistic-table-infantry-color); }
  table tbody tr:nth-child(2) { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(3) { background-color: var(--logistic-table-vehicle-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-supply-units">

|  Nr  | Supply Units            | Beschreibung/Inhalt                                                                                                                             |
|:----:|:------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------|
| 0-01 | **Platoon Supply Unit** | 4x Infanteriemunition (pro Squad)<br> 2x Granaten (inkl. Granatwerfer)<br> 1x Medizinische Vorräte (Pro Platoon/Infanterie)<br> 1x Panzerabwehr |
| 0-02 | **Vehicle Supply Unit** | Fahrzeugmunition-Palette/-Box Treibstoff-Palette Betankung und Aufmunitionierung durch Logistiker/Combat Engineer                               |
| 0-03 | **Vehicle Repair Unit** | Fahrzeugreparatur-Palette Ersatzreifen (in Box) Reparatur durch Logistiker/Combat Engineer                                                      |

</div>

#### Infanterieversorgung

<style>
.logistic-table-infantry-supply {
  table tbody tr { background-color: var(--logistic-table-infantry-color); }
  table tbody tr:nth-child(8) { background-color: var(--logistic-table-lead-color);  }
  table tbody tr:nth-child(10) { background-color: var(--logistic-table-medic-color);}
  table tbody tr:nth-child(11) { background-color: var(--logistic-table-logistic-only-color);  }
  table tbody tr:nth-child(12) { background-color: var(--logistic-table-lead-color);  }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-infantry-supply">

|  Nr  | Infanterieversorgung                          | Beschreibung/Inhalt                                                                                                          |
|:----:|:----------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|
| 1-01 | Infanteriemunition (Pro Squad)                | Gewehrmunition für alle Infanterierollen                                                                                     |
| 1-02 | Panzerabwehr                                  | 2x M136 (HEAT), Raketen für MAAWS Werfer                                                                                     |
| 1-03 | Flugabwehr                                    | 2x FIM-92 Stinger Werfer, 6x FIM-92-Raketen                                                                                  |
| 1-04 | Granaten (inkl. für Granatwerfer)             | Explosiv-& Rauchgranaten (inkl. 40mm)                                                                                        |
| 1-05 | Nachtkampf-Ausstattung                        | NVGs, Flares (inkl. 40mm), Knicklichter, IR-Stroboskope                                                                      |
| 1-06 | Sprengstoff&Minen-Kiste                       | 2x Minensucher, 20x APERS Minenwerfer, 10x Panzerabwehrminen, 20x M4A1 SLAM, 20x Stolperdraht-Leuchtrakete, 20x Sprengladung |
| 1-07 | Funkturm Kiste                                | 5x Funkmast, 5x Funkantenne zum Montieren auf Funkmast (Ersetzt SATCOMS)                                                     |
| 1-08 | Führungskiste                                 | Spezialkiste mit Tablets, Tabs, Rauchgranaten und Lasermarkierer                                                             |
| 1-09 | QRF/Pararescue-Versorgung                     | Munitionskiste exklusiv für die Bewaffnung der QRF/Pararescue                                                                |
| 1-10 | Medizinische Vorräte (Pro Platoon/Infanterie) | Kiste mit Sanitätsmaterial, das ein gesamtes Platoon versorgen sollte                                                        |
| 1-11 | Logistiker-Versorgung                         | Kiste mit Werkzeugen der Logistik                                                                                            |
| 1-12 | UAV-Kiste                                     | 10x UAV-Batterie, 1x UAV-Terminal, 2x UAV (Darter), 4x Fernmarkierer                                                         |
| 1-13 | "Emotional Support Chest"                     | Eine Kiste, reichlich "Crayons" für die Sorgen des einfachen Marines                                                         |
| 1-69 | Kleine Kiste (leer)/Große Kiste (leer)        | Dient für Sonderbestellungen                                                                                                 |

</div>

#### Fahrzeugversorgung

<style>
.logistic-table-vehicle-supply {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(7) { background-color: var(--logistic-table-air-color);  }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-vehicle-supply">

|  Nr  | Fahrzeugversorgung                                 | Beschreibung/Inhalt                                                       |
|:----:|:---------------------------------------------------|:--------------------------------------------------------------------------|
| 2-01 | Ersatzreifen                                       | Bei mehr als einem Ersatzreifen bitte **2-08** anfordern.                 |
| 2-02 | Ersatzkette                                        |                                                                           |
| 2-03 | Fahrzeugmunition-Palette Oder Fahrzeugmunition-Box | Frachtpalette, um Fahrzeuge aufzumunitionieren oder die Pylonen zu ändern |
| 2-04 | Fahrzeugreparatur-Palette                          | Frachtpalette, um Fahrzeuge komplett zu reparieren                        |
| 2-05 | Treibstoff-Palette                                 | Frachtpalette, um Fahrzeuge aufzutanken (3406l)                           |
| 2-06 | Ersatzreifen (in Box)                              | Frachtkiste, vorbefüllt mit 20 Ersatzreifen                               |
| 2-07 | Seahawk Hoist                                      | Seilwinde, die an Seahawk-Modellen montiert werden kann.                  |

</div>

#### Schwere Waffen

<style>
.logistic-table-artillery-supply {
  table tbody tr { background-color: var(--logistic-table-infantry-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-artillery-supply">

|  Nr  | Schwere Waffen/Artillerie  | Beschreibung/Inhalt                                                                                        |
|:----:|:---------------------------|:-----------------------------------------------------------------------------------------------------------|
| 3-01 | M2HB (Verpackt)            | HMG auf Dreibein montiert, wird stehend bedient                                                            |
| 3-02 | M2-Munition                | 10x Gurte mit Leuchtspur (rot)                                                                             |
| 3-03 | MK19 (Verpackt)            | GMW auf Dreibein montiert, wird sitzend bedient                                                            |
| 3-04 | MK19-Munition              | 12x HE, 4x HEDP, 8x Kanister                                                                               |
| 3-05 | M41A4 TOW (Verpackt)       | Statische AT auf Dreibein montiert, wird kniend bedient                                                    |
| 3-06 | TOW-Munition               | 2x BGM-71E TOW-2A (Fahrzeugbekämpfung) 3x BGM-71H Bunker Buster (Bekämpfung von Stellungen und Infanterie) |
| 3-07 | FIM-92 Stinger - Plattform | Statische Luftabwehrstation, nicht Radar-gestützt                                                          |

</div>

#### Landfahrzeuge

<style>
.logistic-table-land-vehicle {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
  table tbody tr:nth-child(2) { background-color: var(--logistic-table-vehicle-color);  }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-land-vehicle">

|  Nr  | Landfahrzeuge      | Sitzplätze | Anmerkungen                          |
|:----:|:-------------------|:----------:|:-------------------------------------|
| 4-01 | AAVP-7A1 (Amtrack) |     21     |                                      |
| 4-02 | LAV-25             |     9      | Aufgerüstet mit verbessertem Thermal |
| 4-03 | HUMVEE (M2)        |     5      |                                      |
| 4-04 | HUMVEE (TOW)       |     5      |                                      |
| 4-05 | LKW (Infanterie)   |     15     |                                      |
| 4-06 | Buggy              |     6      |                                      |

</div>

#### Luftfahrzeuge

<style>
.logistic-table-air-vehicle {
  table tbody tr { background-color: var(--logistic-table-air-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-air-vehicle">

|    Nr    | Luftfahrzeuge       | Sitzplätze | Zweck/Nutzen                    |
|:--------:|:--------------------|:----------:|:--------------------------------|
|   5-01   | UH-1Y Venom         |     11     | Infanterietransport             |
|   5-02   | MH-60M DAP MLASS    |     11     | Patienten-/Frachttransport      |
| ~~5-03~~ | ~~CH-53E (GAU-21)~~ |   ~~27~~   | ~~Fracht-/Infanterietransport~~ |
|   5-04   | AH-1Z Viper         |     2      | CAS                             |
|   5-06   | F/A-18C             |     1      | Luftüberlegenheitsjäger         |

</div>

#### Wasserfahrzeuge

<style>
.logistic-table-sea-vehicle {
  table tbody tr { background-color: var(--logistic-table-vehicle-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-sea-vehicle">

|  Nr  | Wasserfahrzeuge     | Sitzplätze | Beschreibung/Inhalt                |
|:----:|:--------------------|:----------:|------------------------------------|
| 6-01 | Schnellboot Minigun |     11     | Kampfboot mit GMW und 7.62 Minigun |
| 6-02 | RHIB                |     8      | Unbewaffnetes Boot                 |
| 6-03 | Schlauchboot        |     5      | Unbewaffnetes Boot                 |
| 6-04 | MK.V SOC            |     33     | Patrouillenboot                    |

</div>

#### Bauvorhaben/Stellungen

<style>
.logistic-table-construction {
  table tbody tr { background-color: var(--logistic-table-logistic-only-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-4 logistic-table-construction">

|  Nr  | Bauvorhaben/Stellungen\*                   | Bauzeit\*  | Beschreibung                                                                            |
|:----:|:-------------------------------------------|:----------:|:----------------------------------------------------------------------------------------|
| 7-01 | Munitionsversteck                          | \~ 15 Min  | Kleines verstecktes Lager für Infanterie Versorgung                                     |
| 7-02 | Versorgungspunkt (Für die Frontversorgung) | \~ 30 Min  | Kleine Stellung nahe der Front, meist an Straße                                         |
| 7-03 | \+ Integration von 1-2 Helipads            | \~ 15 Min  | Inkl. Versorgung für Helis                                                              |
| 7-04 | \+ Integration eines Feldlazaretts         | \~ 15 Min  | Medizinisches Gebäude                                                                   |
| 7-05 | Kleine FOB                                 | \~ 120 Min | Beinhaltet 7-03, 7-04 und ein Lager für Ersatzfahrzeuge                                 |
| 7-06 | Minenfeld AP je 100m                       | \~ 30 Min  | Linie, wird ausgelegt mit Minenwerfern                                                  |
| 7-07 | Minenfeld AT je 50m                        | \~ 30 Min  | Minenfeld mit AT-Minen auslegung ggf. in Zick-Zack Muster                               |
| 7-08 | Kleine Fire Support Base                   | \~ 60 Min  | Bunkerstellung mit mehreren schweren Waffen                                             |
| 7-09 | Flexible Bauvorhaben                       |  Variabel  | Stacheldraht-Konstruktionen, Stellungen, Fahrzeugsperren, Aufbau von Fallen, Brückenbau |

</div>

\*= Die Bauzeiten sind pragmatisch eingeschätzt und werden voraussichtlich kürzer sein.

#### Wartung Luftfahrzeuge

<style>
.logistic-table-air-vehicle-maintenance {
  table tbody tr { background-color: var(--logistic-table-air-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-air-vehicle-maintenance">

| Nr   | Wartung Luftfahrzeuge | Beschreibung/Inhalt |
|:-----|:----------------------|:--------------------|
| 8-01 | Reparatur             |                     |
| 8-02 | Betankung             |                     |
| 8-03 | Aufmunitionieren      |                     |

</div>

#### Sonstiges

<style>
.logistic-table-others {
  table tbody tr { background-color: var(--logistic-table-logistic-only-color); }
}
</style>

<div markdown="1" class="logistic-table logistic-table-3 logistic-table-3 logistic-table-others">

| Nr   | Sonstiges                            | Beschreibung/Inhalt                                                                                   |
|:-----|:-------------------------------------|:------------------------------------------------------------------------------------------------------|
| 9-01 | Überführen/Transport eines Fahrzeugs | Falls Fahrzeuge in die Basis zurück oder zu einer verlegt werden müssen aufgrund eines Lufttransports |
| 9-02 | Wracks bergen                        | Logistiker formen ein Bergungskommando, um ein Wrack zu bergen.                                       |
| 9-03 | Minenräum-Kommando                   | Falls Minenfelder geräumt werden sollen.                                                              |
| 9-04 | Sonderauftrag                        | Inhalt wird mit Logistikleitung besprochen und festgelegt, sofern Kapazitäten vorhanden sind.         |

</div>
