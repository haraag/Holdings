## Verk

700, 710 och 711 är komplicerade fält i MARC21 som kan uttrycka olika saker om en agent, medverkande, relationer, och att en instans innehåller flera verk.
Länka i första hand till befintliga auktioriteter för personer, organisationer och möten. Om det inte finns en auktoritet så kan du skapa en auktoritet. Se hjälpen för att Skapa ny agent Person samt Organisation. Det finns även hjälp för att redigera befintliga auktoriteter.
I den första versionen av Nya Libris bör man inte länka till eller skapa verk.
Den här hjälpen visar hur man skapar relationer av olika typer. Se även hjälp för att lägga till Agenter - Personer samt Organisationer



### Relationer
Medverkande och funktion
Välj *Medverkan* när en agent har en relation till det verk som beskrivs i instansen.
* Medverkan och funktion / Medverkan / Agent / Person (700 1/- ‡a)
    Länka till entitet.
    I undantagsfall, skapa lokal entitet och välj Person
  ```Exempel: Andersson, Frans, 1962-```

  * Funktion - lägg till vid Medverkan (700 ‡4)
    Länka till entitet.
    ```Exempel: relator/trl (= översättare)```



#### Flera verk kopplade till instansen
Primär medverkan
Välj *Primär medverkn* när agenten har relation till ett annat verk än det som beskrivs i instansen
* Har del / skapa lokal entitet - välj Verk (långt ner i listan - blir lättare när man kommer att kunna länka till verk)
  * Har titel / Huvudtitel  - skriv in titeln
  ```Exempel: Forellkvintetten```
  Fler delfält att lägga till:
    * Språk  / Benämning (700 ‡l)
    *(700 ‡m)
    (700 ‡o)
    (700 ‡r)
    (700 ‡s)

  * Medverkan och contribution / Primär contribution / Agent
  ````Exempel: Schubert, Franz , 1797-1828
