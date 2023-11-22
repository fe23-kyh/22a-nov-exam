# Memory game
**Deadline**: 1a December 17:00.

Examiniationen för kursen Javascript del 1 är att skapa ett memoryspel i grupper om 3. Bedömningen sker via inspelade videopresentationer, **se bedömning längre ner**.

Se pdf:en "[MemoryGameRulesAndDesign](MemoryGameRulesAndDesign.pdf)" för design och spelregler! Obs. Allt under wireframes är **endast** designförslag och är öppen för omtolkning.

## Grupper

Registera grupperna på omnius under kursmaterial.

## Kravspecifikation

* Ett memoryspel som föjer de grundregler som specificeras i pdf:en "[MemoryGameRulesAndDesign](MemoryGameRulesAndDesign.pdf)"
* Spelet ska hantera två spelare
* Spelet ska innehålla minst 12 memory par

### Friviligt krav
Dessa krav är förslag och bör inte tolkas som ett *måste* krav för ett "högre" betyg. För en beskrivning av vad som krävs för ett högre betyg, se betygskriterier för betyget VG.
* Gör så att kort-flip:et animeras
* Skapa en hiscore som sparas i localStorage (se [mdn localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage))
* Lägg till datorstyrd spelare

## Design (avgränsningar)
Designen är sekundär. Huvudregeln är att det finns minst 12 stycken synliga memory par som går att vända på vid knapptryck och att poängen registreras för respektive spelare.

Finns inget krav på responsive design.

## Presentation (videoinspelad)

Innan deadline ska en indivudell videopresentation skickas in via omnius. Videon måste uppfylla följande tekniska krav:
1. Studerande måste vara synlig i minst 15 sekunder under videoinspelningen.
2. Videon får **inte** överstiga 4 minuter (240 sekunder).
3. Ljudkvaliten ska vara accepterbar och det ska gå att höra den inspelades röst under hela inspelningen.
   
Följande ska presenteras under inspelningen.
### Introduktion (ca 1 minut)

- Namn på individ
- Den största utmaningen i projekarbetet
- Beskriv fördelning av arbetet mellan deltagarna
  
### Användargränssnittet (ca 1 minut)

Presentera följande funktioner i det grafiska gränssnittet
1. Starta spelet med två spelare
2. Hitta ett par
3. Visa att poängen för spelaren uppdateras
4. Återupprepa 2. och 3. tills att en spelare har 2 poäng

### Koddemo (max 2 minuter)

Välj ut de **3** kodfunktioner som du anser viktigast i programmet och presentera följande
- Vad är respektive funktions syfte?
- Vad sker i det grafiska gränssnittet när funktionen körs?

Obs. Det är viktigare att du beskriver (med ord) vad som händer i det grafiska gränssnittet snarare än att visa vad som händer i UI:n.

## Inlmämning

Via omnius skicka in följande
- Videoinspelning
- Länk till github repo med fullständig källkod

## Betyskriterier

### Godkänt

För betyget godkänt ska memoryspel och videoinspelning vara inlämnad enligt kravspecifikationen. Minst två av funktionerna i inspelningen ska presenteras med ett godtagbart syfte och med någon koppling till det grafiska gränssnittet.

### Väl godkänt

För betyget väl godkänt ska samtliga krav för godkänt uppfyllas samt samtliga funktioner beskrivas med ett lämpligt syfte och med en tydlig koppling till det grafiska gränssnittet. Vidare ska samtliga funktioner vara av stor relevans för kodens körbarhet.


## Återkoppling

Sker via ominus senast 3 veckor efter avslutad kurs i samband med kursbetyget.

