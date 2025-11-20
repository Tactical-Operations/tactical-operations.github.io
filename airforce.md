# Air Force

## Operationsübersicht

### Wichtige Informationen

#### LZ 4-Liner:

<div markdown="1" class="airforce-table airforce-lz-4-liner">

| LZ Name |     Feindlage     | Ingress/Egress | Markierung |
|:-------:|:-----------------:|:--------------:|:----------:|
|    -    | (grün, gelb, rot) |   (optional)   | (optional) |

</div>

#### CAS

<div markdown="1" class="airforce-table airforce-gameplan">

|     |     Gameplan      |
|:---:|:-----------------:|
| 1\. |    Einsatz Typ    |
| 2\. |      BOT/BOC      |
| 3\. | Waffenanforderung |

</div>

#### 9/5-Liner

<div markdown="1" class="airforce-table airforce-9-liner airforce-5-liner">

|     |          9-Liner           |     |            5-Liner            |
|:---:|:--------------------------:|:---:|:-----------------------------:|
| 1\. |          Ingress           | 1\. |         Ziel Position         |
| 2\. |          Richtung          | 2\. |       Ziel Beschreibung       |
| 3\. |    Distanz zum Ziel IP     | 3\. |        Ziel Markierung        |
| 4\. |      Ziel Höhe (ASL)       | 4\. |      Freundliche Kräfte       |
| 5\. |     Ziel Beschreibung      | 5\. | Hinweise oder Einschränkungen |
| 6\. |       Ziel Position        |     |                               |
| 7\. |         Markierung         |     |                               |
| 8\. | Eigene Kräfte (Markierung) |     |                               |
| 9\. |           Egress           |     |                               |
|     |          Hinweise          |     |                               |

</div>

#### BHA

<div markdown="1" class="airforce-table airforce-bah">

|     | BHA \- Ergebnis des Waffeneinsatzes |
|:---:|:-----------------------------------:|
| 1\. |               Effekt                |
| 2\. |                 BDA                 |
| 3\. |               Re-run                |

</div>

#### Mission 3-Liner (nur für Piloten)

<div markdown="1" class="airforce-table airforce-mission-3-liner">

|          Mission Typ          |  Ort (AO)   | Zu kontaktierende Einheit |
|:-----------------------------:|:-----------:|:-------------------------:|
| A-Recon/ CAS/ QRF/ Pararescue | z.B. POI001 |   z.B. Green Ant auf 68   |

</div>

#### Brevity Terms:

**AO**: Area of Operation  
**MSR**: Main Supply Route  
**BOT**: Bomb on Target (Bekämpfen von Ziel→Benötigt Sicht auf das Ziel(Tally), für Freigabe.)  
**BOC**: Bomb on Coordinate (Bekämpfen von Koordinate→ohne Sicht auf Ziel.)  
**BDA**: Battle Damage Assessment  
**BHA**: Battle Hit Assessment  
**Cleared Hot**: Waffenfreigabe für Anflug erteilt.  
**Cleared to Engage**: Waffenfreigabe für mehrere Anflüge  
**Tally**: Sicht auf Ziel (**No Joy**: keine Sicht auf Ziel)  
**Bingo**: Treibstoff reicht nur für Rückflug.  
**Winchester**: Keine Munition (Winchester Guns: Keine Munition für Gun).  
**Bogey**: Unidentifiziertes Luftfahrzeug, bei dem noch keine Freund-Feind-Bestimmung vorliegt.  
**Bandit**: Identifiziertes feindliches Luftfahrzeug.  
**Kill**: Befehl, ein Ziel zu zerstören.  
**Splash**: Bestätigung, dass das Ziel abgeschossen und zerstört wurde.  
**Abschuss Luft/Luft Rakete**: Fox1 (halbaktives Radar), Fox2 (infarot), Fox3 (aktiv Radar).

#### Smoke:

**Grün**: Freund Markierung  
**Gelb**: JTAC Reserviert  
**Rot**: Feind Markierung  
**Blau**: LZ Markierung  
**Orange**: JTAC Reserviert  
**Violet**: Medevac  
**Weiß**: Verschleierung

#### Flares:

**Weiß**: Beleuchtung  
**Grün**: Freund Markierung  
**Rot**: Feind Markierung

#### Lasercodes

<div markdown="1" class="airforce-table airforce-important-frequences">

|       Unit        |    Callsign    | Lasercode-Nr. | JTAC Channel Name/Nr. |
|:-----------------:|:--------------:|:-------------:|:---------------------:|
|  Triton HQ JTAC   |    Triton 8    |     1113      |      TRITON JTAC      |
| Leviathan Platoon | Leviathan JTAC |     1114      |       LEVI JTAC       |
| Barracuda Platoon | Leviathan JTAC |     1115      |      BARRA JTAC       |

</div>

Logistik für RRR auf dem *LOGISTIC* Funkkanal

#### Karten Markierungen

**IP**: Initial Point (Punkt, von dem ein Anflug gestartet werden kann).  
**HP**: Holding Point (Punkt, an dem Hubschrauber warten und **nicht hovern**).  
**HA**: Holding Area (Aufenthaltsraum für Hubschrauber) → darf nur von ALO erstellt werden.  
**ACA**: Aircraft Control Area (Aufenthaltsraum für (Luft-Boden)) → darf nur von ALO erstellt werden.  
**CAP**: Combat Air Patrol Zone (Partrouillienbreich für Abfangjäger) → darf nur von ALO erstellt werden.  
**LZ**: Landing Zone → muss auf c-Tab oder JVMF markiert werden, → darf nicht verschoben werden.

### JTAC

#### Ablauf:

1. Eine Anfrage für Luftunterstützung wird auf dem *REQUEST* Funkkanal an die jeweilige Einheit gestellt.
   Dort wir nur geklärt: wer? Funkkanal? Weitere Klärungen auf dem jeweiligen JTAC-Funkkanal.
    * Beispiel: Hammerhead hier Barracuda JTAC benötigen CAS. Kommen. - Hier Hammerhead, verstanden wechseln auf
      Funkkanal Barracuda JTAC. Ende.
2. Das Luftfahrzeug meldet sich auf dem Funkkanal JTAC an.
3. Klärung der Anfrage wird auf dem JTAC Funkkanal abgehandelt - Aufträge werden durchgeführt
4. Sobald die Aufträge durchgeführt wurden, entlässt der JTAC die Einheit.

#### Wichtige Punkte

* Aufträge sollten in dieser Reihenfolge priorisiert werden: QRF/Pararescue, CAS, A-Recon.
* Lufteinheiten verwalten sich im Rückraum selbstständig und priorisieren Aufträge selbstständig.
* Die selbstständige Priorisierung kann durch Triton 8 (Triton HQ JTAC) überschrieben werden.

### Piloten

#### Ablauf:

1. Das Luftfahrzeug wird auf dem *REQUEST* Funkkanal angefragt.
    * Beispiel: Hammerhead hier Barracuda JTAC benötigen CAS. Kommen. - Hier Hammerhead, verstanden wechseln auf
      Funkkanal Barracuda JTAC. Ende.
2. Das Luftfahrzeug meldet sich auf dem Funkkanal des JTACs an, bei CAS Fliegern müssen auch die Waffen aufgezählt
   werden.
3. Bis zum Abmelden stehen die Luftfahrzeuge unter der Kontrolle des JTACs
4. Nach abgeschlossener Mission wird der JTAC Funkkanal verlassen und sich wieder auf dem *REQUEST* Funkkanal
   angemeldet.

#### Wichtige Punkte

* Piloten müssen während Einsätzen auf dem Funkkanal *AIR SPACE* angemeldet sein, für die
  Piloten-zu-Piloten-Kommunikation.
* Auch am Boden sollte jede Einheit auf dem Funkkanal *AIR SPACE* erreichbar sein.
* Alle Luftfahrzeuge müssen vor dem Starten den näheren Luftraum mithilfe des cTabs auf landende Helikopter prüfen, ggf.
  Absprechen auf dem *AIR SPACE* Funkkanal.
* Bei der Landung auf Schiffen müssen die Positionslichter aktiviert werden zur Kenntlichmachung des Luftfahrzeuges.
* Das Durchfliegen einer nicht zugewiesenen ACA oder HA sollte vermieden werden.

Bei __weiteren Fragen__
im [Discord \#air-force-chat](https://discord.com/channels/1230998538926952578/1234144188338012170) nachfragen.
