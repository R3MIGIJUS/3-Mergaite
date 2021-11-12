# Procesas

- [ X ] Pradine failu sistema :
  - index.html
  - .gitignore
- [ X ] Paviesinti puslapi per Github Pages, gauti URL
- [ X ] README.md failo sukurimas
  - skirtas aprašyti kuriama projektą, kas ir ką atlieką
  - iterpti nuoroda i daroma dizaina
  - iterpti nuoroda kur musu projekto kodas gali buti pamatytas
- [ X ] Atlikti dizaino analize
- [ X ] Parašyti HTML failą
- [ X ] Išsikirpti nuotraukas ir jas panaudoti
  - png failas bus naudojamas dėl permatomamo fono galimybės
  - panaudoti realytu kelia nuotraukai įterpti
- [ X ] Aprašome stiliu
  - Turinys turi buti centre
  - Pagrindinis turinio plotis fiksuotas, jis nekis, ekrano plotą mažinant
  - stilių (CSS) atskirti nuo HTML

# HTML/CSS rasymo strategija
- Issirasyti kiek imanoma HTML 
- Isisrasyti CSS selektorius
- Pradedant nuo labiausiai tevinio elemento is virsaus surasome kiekvienam reikiama stiliu


Pasiskaitymui apie markdown kalbos naudojimą .md :
https://www.markdownguide.org/basic-syntax/


>Viso turinio centravimui naudojama CSS funkcija calc(100% - 800px)/2  
//100% esamo ekrano atimama 800px turinio ir padalinama is 2, tam kad is abieju turinio pusiu butu vienodi tarpeliai. Keičiantis ekrano ar narsykles dydziui, turinys liks viduryje, tai galioja jei ekranas bus didesnis nei 800px //

CSS taisyklė, paveldimos gali būti tik teksto rasymo stiliaus savybės. Elemento plotis nera teksto savybe, todel nera ji paveldima. Todel negali buti naudojama viename tage, turi buti atskirai kiekvienam tagui nurodyta elemento plotis, dydis ir t.t.

**Padding** savybe išpučia patį elementą. 
**Margin** savybe padaro tarpeli aplink elementa norima kryptimi.