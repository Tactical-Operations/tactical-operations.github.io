#### Logistikanfragen

##### Ablauf:

1. Es wird auf dem *REQUEST* Funkkanal Kontakt mit **Triton 4** aufgenommen.  
2. Triton 4 bestätigt **Aufnahmebereitschaft** oder **verzögert die Anfrage** falls notwendig.
3. Eine Logistikanfrage wird gestellt. Dabei werden folgende Punkte nachfolgend geklärt:  
    3.1. Was für eine Logistikleistung? (Siehe Bestellkatalog und Supply Units)  
    3.2. Grober Lieferort (Gibt es eine LZ/DZ?)  
    3.3. Ist ein Lufttransport möglich?  
4. Auf Rückfragen von Triton 4 warten oder die Auftragsbestätigung annehmen.  
5. Nach **Auftragsbestätigung mit ETA** kann der *REQUEST* Funkkanal verlassen werden.  
6. Warten bis:  
    6.1. sich ein **Lufttransport (Capybara)** auf dem Platoon JTAC Funkkanal meldet. (Dies ist zu erwarten beim Transport von Infanterieversorgung)  
    6.2. sich ein **Bodentransport (Capybara)** auf dem Platoon Actual Funkkanal meldet.  
    6.3. sich ein **Combat Engineer Team (Capybara)** entweder für einen Auftrag oder den Abschluss von diesem auf der Platoon Actual Funkkanal meldet.  

##### Beispiel:

<style>
.logistic-request-example-request li:nth-child(odd) {  background-color: #ea9999; }
.logistic-request-example-request li:nth-child(even) {   background-color: #ffe599; }
</style>

<div markdown="1" class="logistic-request-example-request">

1. “Triton 4, hier Otter, beantragen Nachschub, kommen.”
2. “Otter, hier Triton 4, bereit für Anfrage, kommen”
3. “Wir brauchen eine Standard Platoon Unit - südwestlich von Rasman, bei Markierung
‘DZ Lima’, Luft-Transport ist nicht möglich, keine sicheren LZ in Reichweite, kommen”
4. “Verstanden. Gibt es eine sichere Anfahrrichtung? Kommen”
5. “Jawohl, gibt es aus Westen, kommen”
6. “So verstanden: Anfahrrichtung Westen, Eine Standard Platoon Unit südwestlich von Rasman bei Markierung ‘DZ Lima’ wird bearbeitet. ETA 15 Minuten. Triton 4 Kommen”
7. “Jawohl, so korrekt, Ende”

</div>

<style>
.logistic-request-example-delivery-arrival li:nth-child(odd) {  background-color: #ffe599; }
.logistic-request-example-delivery-arrival li:nth-child(even) {  background-color: #ea9999; }
</style>

Einige Zeit später

<div markdown="1" class="logistic-request-example-delivery-arrival">

1. “Otter HQ, hier Capybara Alpha, kommen aus Westen zu ‘DZ Lima’ mit Nachschub, kommen.”
2. “Otter HQ, verstanden. Lage ist sicher. Ende.”

</div>
