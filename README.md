## Mijn oba
Ontwerp en maak een familieoverzicht voor de website van mijn OBA.

# Inhoudsopgave

- [Beschrijving](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#beschrijving)

- [Kenmerken](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#kenmerken)

- [Bronnen](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#bronnen)

- [Licentie](https://github.com/Khdulkadir/fix-the-flow-interactive-website/tree/main#licentie)


## Beschrijving
Als oba-lid wil ik in de omgeving van mijn OBA een overzicht van activiteiten van al mijn familieleden kunnen zien.
In deze sprint staat het maken van een interactieve website centraal. Voor deze opdracht kies je een user Story waarin een gebruiker iets moet doen, zoals het toevoegen van informatie aan een agenda of stap voor stap door een vragenlijst klikken, een chat-formulier of bijvoorbeeld een filter systeem. Als een gebruiker interactie heeft met een systeem, moet je goede feedback/feedforward ontwerpen en maken. Zo weet een gebruiker wat die kan verwachten en of de actie gelukt is.

Deze sprint ben ik helemaal opnieuw begonnen op advies van de leraar. Dit zodat ik leer om eerst te bouwen voor de mobiel. Ik heb voor deze sprint gekozen voor twee verschillende interacties/animaties. Dit is het in en uitklappen van de navigatie en het aanzetten van dark mode. Voor meer toegankelijkheid heb ik gekozen om een dark mode te maken (ik wilde dit ook in de vorige sprint doen). Ik heb een toggle animatie gemaakt dat als je op de knop klikt, de toggle naar rechts gaat, en wanneer je er nogmaals op klikt, de toggle weer terug naar links gaat. Voor de navigatie heb ik iets soortgelijks gemaakt. Wanneer je op de knop drukt, gaat de navigatie zichzelf inklappen waardoor je alleen nog de icoontjes ziet staan. Wanneer je weer op de knop drukt, klap de navigatie weer uit en zie je meer informatie. Hieronder zal ik de animaties laten zien:

## Desktop
### Ingeklapt
![desktop-ingeklapt](https://user-images.githubusercontent.com/112861033/212927779-9150f9b2-011b-43dd-ba47-8c3c65ea37a0.jpg)
### Uitgeklapt
![Desktop-uitgeklapt](https://user-images.githubusercontent.com/112861033/212927848-5c256b91-e435-4c51-a5ba-5bd426d3b18c.jpg)
### Dark mode
![Desktop-darkmode](https://user-images.githubusercontent.com/112861033/212927930-6e44242f-8d42-46d3-8e32-a46545b06c1b.jpg)

## Mobiel
### Ingeklapt
![Mobiel-ingeklapt](https://user-images.githubusercontent.com/112861033/212928056-3f96c0a8-3702-4078-91c4-0520b942803d.jpg)
### Uitgeklapt
![mobiel-uitgeklapt](https://user-images.githubusercontent.com/112861033/212928073-c6c12b5c-a0d9-49b9-a7c3-673bf10715e1.jpg)
### Dark mode
![Mobiel-darkmode](https://user-images.githubusercontent.com/112861033/212928093-b538ef48-fd68-4a00-ba4b-731123d6be4b.jpg)

## Kenmerken
De website is gemaakt met HTML en CSS.

Het navigatiemenu van het familieoverzicht is al geleverd door de OBA zelf. Hierdoor was er alleen behoefte om het main gedeelte van de familieoverzicht te bouwen.


**HTML**
De main is opgedeeld in twee secties. De eerste sectie is een h1 met een achtergrondfoto als banner:

<main> <section class="home flex"> <h1 class="familienaam">Familieoverzicht</h1>   </section>

De tweede sectie is een ul met 5 accountleden en een icon om een 6de account toe te voegen. De list items zijn responsive gemaakt doormiddel van flex.

<section class="accounts"> <h2>Leden:</h2>

        `<ul class="account-list">`
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
Het was voor de opdrachtgever belangrijk om de stijlboek van OBA te hanteren. De font font-family: "AvenirMedium"; en kleur background-color: #ff1e1e; heb ik daarom meerdere keren gebruikt in de stijlgeving.



## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
