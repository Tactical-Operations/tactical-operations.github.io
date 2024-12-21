## Funkplan Triton Company

![Image](./assets/tacops-2-radio-communication-plan.png)

**Link: [Funkplan im Detail](./assets/tacops-2-radio-communication-plan.png)**   

## Funkplan als Tabelle

<style>
.radio-communication-plan { 
  /* SOS - Emergency */
  table tbody tr:nth-child(1) { background-color: var(--logistic-table-medic-only-color);  }

  /* Triton Platoon */
  table tbody tr:nth-child(n+2):nth-child(-n+3) { background-color: var(--logistic-table-lead-color);  }

  /* Logistic */
  table tbody tr:nth-child(4) { background-color: var(--logistic-table-logistic-only-color);  }

  table tbody tr:nth-child(n+5):nth-child(-n+8) { background-color: var(--logistic-table-air-color);  }

  table tbody tr:nth-child(9) { background-color: var(--logistic-table-infantry-color);  }
  table tbody tr:nth-child(10) { background-color: var(--logistic-table-infantry-color);  }

  table tbody tr:nth-child(11) { background-color: var(--logistic-table-lead-color);  }
  table tbody tr:nth-child(12) { background-color: var(--logistic-table-lead-color);  }

  /* Otter and Barracuda */
  table tbody tr:nth-child(n+13):nth-child(-n+30) { background-color: var(--logistic-table-infantry-color);  }
  /* Alligator */
  table tbody tr:nth-child(n+31):nth-child(-n+37) { background-color: var(--logistic-table-vehicle-color);  }
  /* Logistic */
  table tbody tr:nth-child(n+38):nth-child(-n+42) { background-color: var(--logistic-table-logistic-only-color);  }
  /* Triton HQ internal */
  table tbody tr:nth-child(43) { background-color: var(--logistic-table-lead-color);  }

  /* Air Assets except Logistic */
  table tbody tr:nth-child(n+44):nth-child(-n+47) { background-color: var(--logistic-table-air-color);  }

  /* Dustoff 9-1 */
  table tbody tr:nth-child(48) { background-color: var(--logistic-table-medic-color);}
  /* Lizard */
  table tbody tr:nth-child(49) { background-color: var(--logistic-table-medic-only-color);  }
  /* TELEMEDIC */
  table tbody tr:nth-child(51) { background-color: var(--logistic-table-medic-only-color);  }


}
</style>

<div markdown="1" class="logistic-table radio-communication-plan">

| Channel Nr. | Kurzname     | Beschreibung               | Platoon            | Squad         | Team             |
| ----------- | ------------ | -------------------------- | ------------------ | ------------- | ---------------- |
| 1           | SOS          | Emergency                  |                    |               |                  |
| 2           | TRITON PLT   | Triton Platoon             |                    |               |                  |
| 3           | TRITON PLT A | Triton Platoon Alternative |                    |               |                  |
| 4           | LOGISTIC     | Logistic Request           |                    |               |                  |
| 5           | OTTER JTAC   | Otter JTAC                 | Otter Platoon      | Platoon Squad |                  |
| 6           | BARRA JTAC   | Barracuda JTAC             | Barracuda Platoon  | Platoon Squad |                  |
| 7           | TRITON ALO   | Triton ALO and JTAC        |                    |               |                  |
| 8           | AIR SPACE    | Air Space                  |                    |               |                  |
| 9           | OTTER PLT    | Otter Platoon              | Otter Platoon      | Platoon Squad |                  |
| 10          | BARRA PLT    | Barracuda Platoon          | Barracuda Platoon  | Platoon Squad |                  |
| 11          | GHOST IN1    | Ghost Crab 1 internal      | Ghost Crab         | Squad 1       |                  |
| 12          | GHOST IN2    | Ghost Crab 2 internal      | Ghost Crab         | Squad 2       |                  |
| 13          | OTTER ACTUAL | Otter Actual intern        | Otter Platoon      | Platoon Squad |                  |
| 14          | OTTER ALPHA  | Otter Alpha                | Otter Platoon      | Alpha Squad   |                  |
| 15          | OTTER AF1    | Otter Alpha Fireteam 1     | Otter Platoon      | Alpha Squad   | Fireteam 1       |
| 16          | OTTER AF2    | Otter Alpha Fireteam 2     | Otter Platoon      | Alpha Squad   | Fireteam 2       |
| 17          | OTTER AF3    | Otter Alpha Fireteam 3     | Otter Platoon      | Alpha Squad   | Fireteam 3       |
| 18          | OTTER BRAVO  | Otter Bravo                | Otter Platoon      | Bravo Squad   |                  |
| 19          | OTTER BF1    | Otter Bravo Fireteam 1     | Otter Platoon      | Bravo Squad   | Fireteam 1       |
| 20          | OTTER BF2    | Otter Bravo Fireteam 2     | Otter Platoon      | Bravo Squad   | Fireteam 2       |
| 21          | OTTER BF3    | Otter Bravo Fireteam 3     | Otter Platoon      | Bravo Squad   | Fireteam 3       |
| 22          | BARRA ACTUAL | Barracuda Actual intern    | Barracuda Platoon  | Platoon Squad |                  |
| 23          | BARRA ALPHA  | Barracuda Alpha            | Barracuda Platoon  | Alpha Squad   |                  |
| 24          | BARRA AF1    | Barracuda Alpha Fireteam 1 | Barracuda Platoon  | Alpha Squad   | Fireteam 1       |
| 25          | BARRA AF2    | Barracuda Alpha Fireteam 2 | Barracuda Platoon  | Alpha Squad   | Fireteam 2       |
| 26          | BARRA AF3    | Barracuda Alpha Fireteam 3 | Barracuda Platoon  | Alpha Squad   | Fireteam 3       |
| 27          | BARRA BRAVO  | Barracuda Bravo            | Barracuda Platoon  | Bravo Squad   |                  |
| 28          | BARRA BF1    | Barracuda Bravo Fireteam 1 | Barracuda Platoon  | Bravo Squad   | Fireteam 1       |
| 29          | BARRA BF2    | Barracuda Bravo Fireteam 2 | Barracuda Platoon  | Bravo Squad   | Fireteam 2       |
| 30          | BARRA BF3    | Barracuda Bravo Fireteam 3 | Barracuda Platoon  | Bravo Squad   | Fireteam 3       |
| 31          | ALLI PLT     | Alligator Platoon          | Alligator Platoon  |               |                  |
| 32          | ALLI ALPHA   | Alligator Alpha            | Alligator Platoon  | Alpha Squad   |                  |
| 33          | ALLI AL1     | Alligator Alpha 1 internal | Alligator Platoon  | Alpha Squad   | Alpha 1 internal |
| 34          | ALLI AL2     | Alligator Alpha 2 internal | Alligator Platoon  | Alpha Squad   | Alpha 2 internal |
| 35          | ALLI BRAVO   | Alligator Bravo            | Alligator Platoon  | Bravo Squad   |                  |
| 36          | ALLI BR1     | Alligator Bravo 1 internal | Alligator Platoon  | Bravo Squad   | Bravo 1 internal |
| 37          | ALLI BR2     | Alligator Bravo 2 internal | Alligator Platoon  | Bravo Squad   | Bravo 2 internal |
| 38          | CAPY PLT     | Capybara Platoon           | Capybara Platoon   |               |                  |
| 39          | CAPY IN1     | Capybara 1 internal        | Capybara Platoon   | Capybara 1    |                  |
| 40          | CAPY IN2     | Capybara 2 internal        | Capybara Platoon   | Capybara 2    |                  |
| 41          | PELI IN1     | Pelican 1 internal         | Pelican 1          |               |                  |
| 42          | PELI IN2     | Pelican 2 internal         | Pelican 2          |               |                  |
| 43          | TRITON HQ    | Triton HQ internal         | Triton HQ          |               |                  |
| 44          | EAGLE INT    | Eagle internal             | Eagle Wing         |               |                  |
| 45          | MORAY IN1    | Moray 1 internal           | Moray 1            |               |                  |
| 46          | MORAY IN2    | Moray 2 internal           | Moray 2            |               |                  |
| 47          | OSPRY IN1    | Osprey 1 internal          | Osprey 1           |               |                  |
| 48          | DUSTOFF 9-1  | Dustoff 9-1 internal       | Dustoff            |               |                  |
| 49          | LIZARD INT   | Lizard 1 internal          | Lizard 1           |               |                  |
| 50          | GHOST PLT    | Ghost Crab Platoon (empty) | Ghost Crab Platoon |               |                  |
| 51          | TELEMEDIC    | Medic Q. and A.            |                    |               |                  |
| 52          | MISC 1       | Miscellaneous 1            |                    |               |                  |
| 53          | MISC 1       | Miscellaneous 2            |                    |               |                  |

</div>

## Rauchfarben

**Grün**: Freund Markierung  
**Gelb**: JTAC Reserviert  
**Rot**: Feind Markierung  
**Blau**: LZ Markierung  
**Orange**: JTAC Reserviert  
**Violet**: Medevac  
**Weiß**: Verschleierung
