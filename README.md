# Matikkaeditorinkaantaja
MEK -matikkaeditorinkääntäjä-

versio v2.1 exe

# Ohjeita matikkaeditorinkääntäjän käyttämiseen.
täältä saa paljon vinkkejä ja tietoa kehittäjän mielenkulusta 

## Mikä ihmeen matikkaeditorinkääntäjä
- matikkaeditorinkääntäjä eli MEK on tarkoitettu lukiolaisille, varsinkin heille jotka opiskelevat pitkää matematiikka tai muita matemaattisia aineita  
- MEK ottaa sisääntulona [matikkaeditorin](https://math-demo.abitti.fi/) (tai muiden kaavakirjoitusohjelmien kuten L'math) LaTeX -koodia ja kääntää sen cas- laskinohjelmistolle sopivaan muotoon  
- esim. LaTeX input: "\frac{6\cdot 7}{14}" --> käännetty versio: "(6*7)/(14)"  
- esimerkki oli vain pieni osa, joka voidaan kääntää  
	- käännettävissä mm. yhtälöryhmät, potenssit, summakaavat ja monia muita  
	- jotkin kääntötilat tunnistavat myös yksiköitä esim. km, mol, s  
	- kääntölistat ja tilojen toiminnat voit löytää alhaalla olevista linkeistä (mm. "ohjeita ohjelman käyttämiseen" ja "merkkimuutokset")  
- kääntö on suunniteltu Ti -Nspire cx cas -laskentaohjelmistolle, mutta se toimii myös suurimmilta osin GeoGebrassa   

## Miksi käyttää matikkaeditorinkääntäjää?  
- Voit laskea nopeammin tunnilla, koska kaikkea ei tarvitse kirjoittaa käsin
- ei enää laskujen kopioimista matikkaeditorista vihkon kautta laskentaohjelmistoon
- vähemmän virheitä: kääntöprosessissa ei tule merkkivirheitä


## !HUOM!  
- Kaikkien tiedostojen TÄYTYY sijaita niiden omissa paikoissa.  
- Itse kansion sijainnilla ei ole väliä.  
- FYSIIKKATILA2 EI OLE VIELÄ TOIMINNASSA  
- Kääntäjän saa käynnistettyä kaksoisklikkaamalla kansiota "matikkaeditorinkääntäjä.pyw" 
	tai pikakuvakkeen kautta.  



## Python ja sen asentaminen
Koneessa täytyy olla asennettuna Python  
Koodi on kirjoitettu versiolla 3.9.5, joten tämän- tai uudemmanversion käyttöä suositellaan.  
Pythonin saa ladattua [Täältä](https://www.python.org/downloads/)  

#### asennusprosessi
	1) asenna python 3.9.(6) [pythonin nettisivuilt](https://www.python.org/downloads/) 
	2) asennusprosessin alussa muista painaa “ADD python 3.9 to PATH”
	3) sen jälkeen voit painaa “Install now”
	4) Tämän jälkeen python asentuu ja on valmis käytettäväksi, kun asennusohjelma niin sanoo
	5) tämän jälkeen voit painaa “close”
		- Huom. Microsoft storen Python ei välttämättä toimi

#### Jos et ole varma, onko Python asennettu: 
	1) Mene komentokehotteeseen painamalla Windows näppäintä ja kirjoittamalla "cmd"  
	2) Kirjoita aukevaan ikkunaan "python --version" (ilman lainausmerkkejä)*  
	3) Jos koneeseesi on asennetty Python, komentokehote ilmoittaa sen version  

 		*komennon voi myös copy pastettaa 


#### Lataa Matikkaeditorinkääntäjä
	1) Lataa oikea MEK versio githubista  (pakatun tiedoston voi ladata sivun alareunasta (Source code (zip)
	2) Pura tiedosto painamalla hiiren oikeaa näppäintä tiedoston päällä ja valitsemalla “Pura kaikki...” ja paina “Pura”
	3) Kun tiedosto on purettu, avautuu purettu tiedosto näkyville
	4) Vie kansio haluamaasi kansioon
	5) voit käynnistää nyt ohjelman painamalla tätä tiedostoa
	6) Kannattaa vielä luoda pikakuvake seuraamalla ohjeita (alapuolella)





=======
- Kääntäjän saa käynnistettyä kaksoisklikkaamalla kansiota "matikkaeditorinkääntäjä.exe" 
	tai pikakuvakkeen kautta.  

## asentaminen

	1) Lataa oikea MEK versio githubista
	2) Pura tiedosto painamalla hiiren oikeaa näppäintä tiedoston päällä ja valitsemalla “Pura kaikki...” ja paina “Pura”
	3) Kun tiedosto on purettu, avautuu purettu tiedosto näkyville
	4) Vie avautunut kansio valitsemaasi kansioon
	5) Kannattaa vielä luoda pikakuvake seuraamalla alapuolella olevia ohjeita
	6) Ohjelman saa käynnistettyä kaksoisklikkaamalla tiedostoa "matikkaeditorinkääntäjä.exe"

#### Pikakuvakkeen luominen*:
	1) klikkaa oikealla hiirinäppäimellä tiedostoa "matikkaeditori.pyw"  
	2) valitse "Luo pikakuvake"  
	3) Pikakuvake ilmestyy hakemistoon ja sen perässä lukee "<tiedostonnimi>- pikakuvake"  
	4) kuvakkeen nimen voi vaihtaa ja sitä voi siirrellä  
	5) Huomaa, että jos siirrät tiedostokansioita, täytyy mahdollisesti 
	      	luoda myös uusi pikakuvake  
	
		*toiminnon voi suorittaa mille tahansa Windows-tiedostolle   


## Asetukset ja muutokset:

#### Kääntäjän värin vaihtaminen:
	1) Käynnistä kääntäjä
	2) Paina "tiedosto"
	3) --> "Muuta tyyliä"
	4) Kirjoita haluamasi väri haluamaasi tekstikenttään*
	5) Voit esikatsella väriä painamalla "esikatsele" tai asettaa sen painamalla "OK"
		- Esikatseltava väri näkyy tekstikentän vieressä pienessä laatikossa
		- Värit voi myös palauttaa alkuperäisiksi painamalla "palauta oletus"
		- Jos "Virhekoodit" -ikkuna on avoinna, sen väri vaihtuu ainoastaa uudelleenavattaessa

		*Ilmoita väri hexadesimaalina (muoto: "#xxxxxx" (x = numero 0-9 tai kirjain a-f))
		  Värejä voit hakea netistä googlaamalla esimerkiksi "hex color picker"

#### Laskentatilan muuttaminen
	1) Käynnistä kääntäjä
	2) Paina asetukset
	3) Paina haluamaasi tilaa*
	4) Oletusasetukset** voi palauttaa napista
	5) Laskentatiloista saa lisää tietoa osiosta "Tilat ja niiden toiminta"

		*huomaa että matematiikka ja fysiikkatiloista voi päällä olla kerrallaan vain yksi 
		**oletuksena päällä on ainoastaan matikkatila

## Tilat ja niiden toiminta

### Laskentatilat  
oletuksena päällä on matematiikkatila  
tilan muuttamiseksi katso osio "Asetukset ja muutokset" --> "Laskentatilan muuttaminen"  
eri tilat muuttavat merkkien käännöksiä  
merkkikäännökset voi tarkistaa editorin mukana tulevasta Excel -tiedostosta

##### Matematiikkatila
	-kääntää kaiken matikan näkökulmasta
	-ei tunnista eikä poista yksiköitä 
        
##### Fysiikkatila 1
	-tunnistaa useita yksiköitä ja poistaa ne 
        
##### Fysiikkatila 2	EI VIELÄ TOIMINNASSA
	-tunnistaa useita yksiköitä ja muuttaa ne _ -muotoon (esim m^2 -->  _m^2)  
	-Lisää yksiköitä ja kreikkalaisia aakkosia saa lisättyä pyynnöstä  

##### geometriatila
	-ottaa käyttöön merkit α β γ δ

### Muut tilat  
toimintoja jotka helpottavat elämää  
ovat usein oletuksena päällä
      
##### älä poista turhia aaltosulkeita
	- toiminto "asetukset" -valikossa
	- poistaa LaTeX kaavasta turhia aaltosulkeita, jotka ovat sinne päätyneet eri syistä
	- auttaa esimerkiksi L'mathin kanssa
	- oletuksena päällä, mutta tilaa voi muuttaa "asetukset" -valikosta
	- kannattaa pitää aina pois päältä kuten oletuksena onkin

##### pikakääntötila
	- toimii "pikakääntö" napista painamalla
	- nopeuttaa laskemista (kaikki toimii yhdellä painalluksella)
	- toiminta:
		  1) liittää käännettävän LaTeX-koodin leikepöydältä
		  2) kääntää sen valituissa laskentatiloissa
		  3) asettaa sen laatikoihin näkyville
		  4) kopioi käännöksen leikepöydälle

## sovelluksen poistaminen
	1) koska sovelluksella ei ole asennusohjelmaa, olet itse sijoittanut kansion ja sen kaikki tiedostot haluamaasi paikkaan
	2) mene kansioon, johon kaikki on tallennettu ja poista kaikki ohjelmistoon kuuluvat tiedostot ja kansiot
	3) muista myös poistaa luomasi pikakuvake
		(jos et muista minne olet tiedostot tallentanut, voit painaa pikakuvakkeesta oikealla hiirinäppäimellä ja valita “avaa tiedostosijainti”)



1.) matikkaeditori.exe  
2.) README.md  
3.) terms and conditions.txt  
4.) data    
5.)    |____ change.log    
6.)    |____ color.dat  
7.)    |____ settings.txt  





ohjelmiston käyttöehdot voit löytää mukana tulevasta tiedostosta "terms and conditions.txt"  

## Ohjeita ja muita tiedostoja  

lisää kuvallisia ohjeita käyttöönottoon löytyy [täältä](https://docs.google.com/document/d/1xKYWsBhS1MESHVi0ALWNzCvWH8a3M2paWLCfXHwJFho/edit?usp=sharing)  
merkkimuutokset löytyvät [täältä](https://docs.google.com/spreadsheets/d/1bi-iejOZ7LSQXTja8hWFj7LcgKMt4z3Aa5pRelak9R8/edit?usp=sharing)  
käyttöehdot läytyvät [täältä](https://docs.google.com/document/d/1m952YhMxpN6ihcMfVcO7xJ0TYGzwajvvKJLnzftqdz0/edit?usp=sharing)  
ohjeita ohjelman käyttämiseen löytyy [täältä](https://docs.google.com/document/d/1DsLcrpI9WRrZpKFShpISrDzh8b6GYNe3oJJxGGmKpiA/edit?usp=sharing)  



Tiedosto päättyy!   kiitos jos luit!  :) 
