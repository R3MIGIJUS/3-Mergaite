# Procesas

- [X] Pradinė failų sistema :
  - index.html;
  - .gitignore;
- [X] Paviešinti puslapį per Github Pages, gauti URL;
- [X] README.md failo sukūrimas:
  - skirtas aprašyti kuriamą projektą, kas ir ką atlieką;
  - įterpti nuorodą į daromą dizainą;
  - įterpti nuorodą kur mūsų projekto kodas gali būti pamatytas;
- [X] Atlikti dizaino analize;
- [X] Parašyti HTML failą;
- [X] Išsikirpti nuotraukas ir jas panaudoti:
  - png failas bus naudojamas dėl permatomamo fono galimybės;
  - panaudoti reliatyvų kelią nuotraukai įterpti;
- [X] Aprašome stiliu:
  - Turinys turi būti centre;
  - Pagrindinis turinio plotis fiksuotas, jis nekis, ekrano plotą mažinant;
  - stilių (CSS) atskirti nuo HTML;

# HTML/CSS rasymo strategija
- Išsirašyti kiek imanoma HTML;
- Išsirašyti CSS selektorius;
- Pradedant nuo labiausiai tevinio elemento iš viršaus surašome kiekvienam reikiama stilių;

**Padding** savybe išpučia patį elementą. 
**Margin** savybe padaro tarpeli aplink elementa norima kryptimi.


Pasiskaitymui apie markdown kalbos naudojimą (.md) :
https://www.markdownguide.org/basic-syntax/


>Viso turinio centravimui naudojama CSS funkcija **calc(100% - 800px)/2**
100% esamo ekrano atimama 800px turinio ir padalinama iš 2, tam kad iš abiejų turinio pusių būtų vienodi tarpeliai. Keičiantis ekrano ar naršyklės dydžiui, turinys liks viduryje, tai galioja jei ekranas bus didesnis nei 800px.

>CSS taisyklė, paveldimos gali būti tik teksto rašymo stiliaus savybės. Elemento plotis nėra teksto savybė, todėl nėra ji paveldima. Todėl negali būti naudojama viename tag'e, turi būti atskirai kiekvienam tagui nurodyta elemento plotis, dydis ir t.t.

# Pain.net Naudojimas
- Norint iškirpti nuotrauką su kuo mažesniu likusiu fonu (Logotipui buvo naudojama) :

<ol>
  <li> Magic wanda -> Tolerance ;</li>
  <li> Ctrl + i;</li>
  <li> Ctrl +Shift + x;</li>
  
</ol>