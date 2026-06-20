## Funkplan Triton Company

![Image](./assets/tacops-3-general-radio-communication-plan.png)

**Link: [Funkplan im Detail](./assets/tacops-3-general-radio-communication-plan.png)**

## Funkplan als Tabelle

<style>
.radio-communication-plan { 
  /* REQUEST */
  table tbody tr:nth-child(1) { background-color: var(--logistic-table-medic-only-color);  }

  /* Triton Platoon */
  table tbody tr:nth-child(n+2):nth-child(-n+3) { background-color: var(--logistic-table-lead-color);  }

  /* JTAC */
  table tbody tr:nth-child(n+4):nth-child(-n+7) { background-color: var(--logistic-table-air-color);  }
  
  /* Leviathan and Barracuda Platoon */
  table tbody tr:nth-child(n+8):nth-child(-n+9) { background-color: var(--logistic-table-lead-color);  }

  /* Leviathan and Barracuda */
  table tbody tr:nth-child(n+10):nth-child(-n+29) { background-color: var(--logistic-table-infantry-color);  }
  /* Alligator */
  table tbody tr:nth-child(n+30):nth-child(-n+31) { background-color: var(--logistic-table-vehicle-color);  }
  /* Logistic */
  table tbody tr:nth-child(n+32):nth-child(-n+34) { background-color: var(--logistic-table-logistic-only-color);  }

  /* Marine Raiders - Ghost Crab */
  table tbody tr:nth-child(n+35):nth-child(-n+37) { background-color: var(--logistic-table-infantry-color);  }

  /* QRF - Trident */
  table tbody tr:nth-child(n+38):nth-child(-n+40) { background-color: var(--logistic-table-medic-color);  }

  /* Triton HQ internal */
  table tbody tr:nth-child(41) { background-color: var(--logistic-table-lead-color);  }

  /* SSC and/or FOB */
  table tbody tr:nth-child(n+42) { background-color: var(--logistic-table-logistic-only-color);  }

}
</style>

<div markdown="1" class="logistic-table radio-communication-plan">

| Channel Nr. | Kurzname       | Beschreibung                  |
|-------------|----------------|-------------------------------|
| 1           | REQUEST        | Anfragen: CAS, Logistik, QRF  |
| 2           | TRITON PLT     | Triton Platoon                |
| 3           | TRITON PLT A   | Triton Platoon Alternative    |
| 4           | LEVI JTAC      | Leviathan JTAC                |
| 5           | BARRA JTAC     | Barracuda JTAC                |
| 6           | TRITON JTAC    | Triton JTAC                   |
| 7           | AIR SPACE      | Pilotenkanal für Air Space    |
| 8           | LEVI PLT       | Leviathan Platoon             |
| 9           | BARRA PLT      | Barracuda Platoon             |
| 10          | LEVI LEAD      | Leviathan Lead intern         |
| 11          | LEVI ALPHA     | Leviathan Alpha               |
| 12          | LEVI AF1       | Leviathan Alpha Fireteam 1    |
| 13          | LEVI AF2       | Leviathan Alpha Fireteam 2    |
| 14          | LEVI BRAVO     | Leviathan Bravo               |
| 15          | LEVI BF1       | Leviathan Bravo Fireteam 1    |
| 16          | LEVI BF2       | Leviathan Bravo Fireteam 2    |
| 17          | LEVI CHARLIE   | Leviathan Charlie             |
| 18          | LEVI CF1       | Leviathan Charlie Fireteam 1  |
| 19          | LEVI CF2       | Leviathan Charlie Fireteam 2  |
| 20          | BARRA LEAD     | Barracuda Lead intern         |
| 21          | BARRA ALPHA    | Barracuda Alpha               |
| 22          | BARRA AF1      | Barracuda Alpha Fireteam 1    |
| 23          | BARRA AF2      | Barracuda Alpha Fireteam 2    |
| 24          | BARRA BRAVO    | Barracuda Bravo               |
| 25          | BARRA BF1      | Barracuda Bravo Fireteam 1    |
| 26          | BARRA BF2      | Barracuda Bravo Fireteam 2    |
| 27          | BARRA CHARLIE  | Barracuda Charlie             |
| 28          | BARRA CF1      | Barracuda Charlie Fireteam 1  |
| 29          | BARRA CF2      | Barracuda Charlie Fireteam 2  |
| 30          | ALLI PLT       | Alligator Platoon             |
| 31          | ALLI PLT A     | Alligator Platoon Alternative |
| 32          | CAPY PLT       | Capybara Platoon              |
| 33          | CAPY ALPHA     | Capybara 1 inter              |
| 34          | CAPY BRAVO     | Capybara 2 inter              |
| 35          | GHOST CRAB     | Ghost Crab Alpha              |
| 36          | GHOST CRAB AF1 | Ghost Crab Alpha Fireteam 1   |
| 37          | GHOST CRAB AF2 | Ghost Crab Alpha Fireteam 2   |
| 38          | TRIDENT PARA   | Trident intern                |
| 39          | TRIDENT MIKE   | Trident Abgesessen            |
| 40          | TRIDENT HOTEL  | Trident Helicopter            |
| 41          | TRITON HQ      | Triton HQ internal            |
| 42          | SSC FOB        | SSC und/oder FOB              |
| 43          | US NAVY        | US Navy Schiffe               |

</div>

## Rauchfarben

**Grün**: Freund Markierung  
**Gelb**: JTAC Reserviert  
**Rot**: Feind Markierung  
**Blau**: LZ Markierung  
**Orange**: JTAC Reserviert  
**Violet**: QRF Reserviert
**Weiß**: Verschleierung
