## Mijn oba
Ontwerp en maak een familieoverzicht voor de website van mijn OBA.

# Inhoudsopgave

- [Beschrijving](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#beschrijving)

- [Kenmerken](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#kenmerken)

- [Bronnen](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#bronnen)

- [Licentie](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#licentie)


## Beschrijving
**User story**: Als oba-lid wil ik in de omgeving van mijn OBA een overzicht van activiteiten van al mijn familieleden kunnen zien.


In deze sprint staat het maken van een interactieve website centraal. Voor deze opdracht kies je een user Story waarin een gebruiker iets moet doen, zoals het toevoegen van informatie aan een agenda of stap voor stap door een vragenlijst klikken, een chat-formulier of bijvoorbeeld een filter systeem. Als een gebruiker interactie heeft met een systeem, moet je goede feedback/feedforward ontwerpen en maken. Zo weet een gebruiker wat die kan verwachten en of de actie gelukt is.

Deze sprint ben ik helemaal opnieuw begonnen op advies van de leraar. Dit zodat ik leer om eerst te bouwen voor de mobiel. Ik heb voor deze sprint gekozen voor twee verschillende interacties/animaties. Dit is het in en uitklappen van de navigatie en het aanzetten van dark mode. Voor meer toegankelijkheid heb ik gekozen om een dark mode te maken (ik wilde dit ook in de vorige sprint doen). Ik heb een toggle animatie gemaakt dat als je op de knop klikt, de toggle naar rechts gaat, en wanneer je er nogmaals op klikt, de toggle weer terug naar links gaat. Voor de navigatie heb ik iets soortgelijks gemaakt. Wanneer je op de knop drukt, gaat de navigatie zichzelf inklappen waardoor je alleen nog de icoontjes ziet staan. Wanneer je weer op de knop drukt, klap de navigatie weer uit en zie je meer informatie. Hieronder zal ik de animaties laten zien:

## Desktop
![Oba Familieoverzicht](https://github.com/Khdulkadir/fix-the-flow-interactive-website/assets/144004145/f53e7eb0-c724-4e4f-8cd1-d94555160903)

## Mobiel
### Ingeklapt
![Oba Familieoverzicht Mobile](https://github.com/Khdulkadir/fix-the-flow-interactive-website/assets/144004145/2ecf9b80-6a31-41c5-938d-5d8b2c41d74c)
### Uitgeklapt
![Oba Familieoverzicht Mobile Menu](https://github.com/Khdulkadir/fix-the-flow-interactive-website/assets/144004145/62dc80f3-6524-4148-b044-41ae9ed9be47)

## Kenmerken
De website is gemaakt met HTML en CSS.

Het navigatiemenu van het familieoverzicht is al geleverd door de OBA zelf. Hierdoor was er alleen behoefte om het main gedeelte van de familieoverzicht te bouwen.


**HTML**
De main is opgedeeld in twee secties. De eerste sectie is een h1 met een achtergrondfoto als banner:

`<main>` `<section class="home flex">` `<h1 class="familienaam">Familieoverzicht</h1>`

De tweede sectie is een ul met 5 accountleden en een icon om een 6de account toe te voegen. De list items zijn responsive gemaakt doormiddel van flex.

`<section class="accounts"> <h2>Leden:</h2>`

        <ul class="account-list">`
            `<li id="account">`
                `<div class="profile-info">`
                    `<img src="./image/icons8-person-48.png" alt="Profile Picture" class="profile-picture">`
                    `<div class="account-details"><p class="typeaccount">(Type account)</p>`
                    `<i class='bx bx-dots-vertical icon dots-vertical'></i>`
                    `<h3>Amber</h3>`
                    `</div>`
                `</div>`
                
                `<ul class="gegevens">`
                    `<li class="boete">• Openstaande boetes: 0.00`
                    `</li>`
                    `<li class="geleend">• Geleende artikelen: 6`
                    `</li>`
                    `<li class="inleverdatum">• Volgende inleverdatum: 06-12-2023`
                    `</li>`
                `</ul>`
                `<button class="selecteer"> Selecteer Profiel</button>`
            `</li>`
**CSS**
Het was voor de opdrachtgever belangrijk om de stijlboek van OBA te hanteren. De font `font-family: "AvenirMedium";` en kleur `background-color: #ff1e1e;` heb ik daarom meerdere keren gebruikt in de stijlgeving.



## Licentie

![OBA](https://www.oba.nl)

This work is licensed under [GNU GPLv3](./LICENSE).
