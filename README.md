> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](https://github.com/fdnd-task/all-human-accessible-website/blob/main/docs/INSTRUCTIONS.md)

# Accessible Website

Ontwerp en maak voor een opdrachtgever een component/pagina/site toegankelijk volgens WCAG richtlijnen.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## User Story
> Toon in een overzicht alle abonnementen van een familie met een verwijzing naar een indiviueel profiel van elk familielid.
> Functies:

> * Familieleden
> * Beschikbare diensten
> * Laatst geleende boeken
> * In te leveren boeken om boete te voorkomen


## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Voor deze opdracht moeten wij een toegankelijke website volgens WCAG richtlijnen met een overzicht van alle abonnementen van een familie met een verwijzing naar een indiviueel profiel van elk familielid maken. Ik en de andere mensen met OBA als opdrachtgever hebben de pagina's verdeeld en daarna op elk van onze pagina naar elkaar doorgelinkt.

Op de pagina waar ik aan gewerkt heb, uitleengeschiedenis, kan je de boeken zien die je in het verleden hebt geleend en daaronder een paar aanbevolen activiteiten van de OBA waar je op kan klikken om doorgeleid te worden naar de OBA informatiepagina van de desbetreffende activiteit.

Bovenaan de pagina staat een zoekfunctie, waar je later specifiek zou kunnen zoeken naar een boek. Daaronder staan een paar filters waar je later op zou kunnen klikken om te sorteren op tijd. Een andere functie aanwezig op deze pagina is de info knop onder de boeken. Als je hier op klikt komt er een venster tevoorschijn met meer informatie over wanneer het boek is uitgeleend, en wanneer het weer is ingeleverd. In dit zelfde venster staan in deze nieuwe versie nu ook aanbevolen boeken gebasseerd op het boek dat je al gelezen hebt.
Ook kan je op de boekcover klikken om doorgeleid te worden naar de oba pagina waar je dat boek weer zou kunnen uitlenen. Op de auteur kan je nu ook klikken voor meer boeken van die auteur.

<!-- Voeg een mooie poster visual toe 📸 -->

### Groot scherm lightmode

![website groot scherm lightmode](https://github.com/Annevd/all-human-accessible-website/assets/144004647/94cae7bf-9336-4d9b-9075-d7788a9efe5e)

### Groot scherm lightmode navigatie uitgeklapt

![website groot scherm navigatie](https://github.com/Annevd/all-human-accessible-website/assets/144004647/9cde1a53-4e93-4601-878b-28d94506fc38)

### Groot scherm darkmode

![website groot scherm darkmode](https://github.com/Annevd/all-human-accessible-website/assets/144004647/57f8dd56-4b32-411f-a376-625b6dd704e6)

### Klein scherm lightmode

![website klein scherm lightmode](https://github.com/Annevd/all-human-accessible-website/assets/144004647/7b81b6c5-df0b-4d39-92da-698909931213)

### Klein scherm lightmode navigatie uitgeklapt

![website klein scherm navigatie](https://github.com/Annevd/all-human-accessible-website/assets/144004647/0f353d2d-84d7-4ee2-931e-9881bd113449)

### Klein scherm darkmode

![website klein scherm dark mode](https://github.com/Annevd/all-human-accessible-website/assets/144004647/cf0faa6d-3301-40ed-961a-0127c458ac6a)


<!-- Voeg een link toe naar Github Pages 🌐-->

[Mijn website](https://annevd.github.io/all-human-accessible-website/)

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

Voor deze website heb ik HTML en CSS gebruikt. De HTML is gestructureerd in articles, divs en een section. De belangrijkste dingen met css zijn de grids op de boekenlijst en op de aanbevolen activiteiten. Daarnaast gebruik ik flex om de boeken, titels, auteur en de info knop onder elkaar te zetten. Verder gebruik ik ```position: fixed;``` om de navigatie altijd vast bovenaan de pagina te houden. Mocht je in deze code willen werken, fork en clone deze repository! Bekijk mijn [wiki](https://github.com/Annevd/all-human-accessible-website/wiki) voor nog meer uitleg over de code!


## Bronnen

* [The A11Yproject](https://www.a11yproject.com/)
* [w3 WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)
* [How to do an accessibilty review](https://web.dev/articles/how-to-review)
* Chrome Lighthouse test

## Licentie


This project is licensed under the terms of the [MIT license](./LICENSE).
