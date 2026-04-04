# WorkOrder System

**TVTPT23A Lopputyö**  
**Nico Nikkinen & Peik Yli-Kuivila**  
**Vamia TVTPT23A**

## Kuvaus
WorkOrder System on C# WinForms -sovellus konepajan työtilausten hallintaan.  
Sovelluksella voidaan hallita tuotteita, tuotteiden osia sekä työmääräyksiä SQLite-tietokannan avulla.

## Teknologiat
- C#
- Windows Forms
- SQLite
- Visual Studio
- Draw.io

## Ominaisuudet
- Työmääräysten luonti
- Tuotteiden lisäys
- Tuotteille osien lisäys
- Osien automaattinen haku valitun tuotteen perusteella
- Työmääräyksen merkitseminen valmiiksi
- Valmiiden työmääräysten näyttäminen
- Paluu MainMenuun back-napeilla

## Käyttöönotto
1. Avaa projekti Visual Studiossa.
2. Varmista että tietokantatiedosto on mukana projektissa.
3. Käynnistä ohjelma painamalla `F5`.
4. Siirry päävalikosta työmääräyksiin tai tuotteiden hallintaan.

## Käyttö
### Tuotteen lisääminen
1. Avaa `ManageProductsForm`.
2. Lisää uusi tuote nimellä ja hinnalla.
3. Valitse lisätty tuote listasta.
4. Lisää tuotteelle osia.

### Työmääräyksen lisääminen
1. Avaa `WorkOrderListForm`.
2. Paina `Add`.
3. Valitse asiakas ja tuote.
4. Sovellus hakee osat automaattisesti valitun tuotteen perusteella.
5. Tallenna työmääräys.

### Työn merkitseminen valmiiksi
1. Avaa työmääräys listasta.
2. Merkitse työ valmiiksi details-näkymässä.
3. Valmis työ poistuu aktiivisista töistä.
4. Valmis työ voidaan näyttää uudelleen valitsemalla `Näytä valmiit`.

## Tietomalli
Tietomalli on suunniteltu Draw.io:lla ja löytyy projektin mukana erillisenä kuvana.  
Tietomalli sisältää työmääräykset, tuotteet, tuoteosat, osat, asiakkaat sekä statukset.
