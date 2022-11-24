<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="img/ui-ux-banner.png" alt="Banner" width="849" height="115">
  </a>

  <h3 align="center">UI / UX Design Cheatsheet</h3>

  <p align="center">
    Sfaturi, resurse și îndrumări care să te ajute să creezi interfețe de aplicații.
    <br />
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet"><strong>Explorează documentația »</strong></a>
    <br />
    <br />
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet/">Engleză</a>
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet/issues">Raportează o Problemă</a>
    ·
    <a href="https://github.com/muresan-gabriel/ui-ux-design-cheatsheet/issues">Contribuie</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Cuprins</summary>
  <ol>
    <li>
      <a href="#despre-proiect">Despre Proiect</a>
    </li>
    <li>
      <a href="#principii-de-bază-în-design">Principii de Bază în Design</a>
      <ul>
        <li>
          <a href="#contrast">Contrast</a>
        </li>
        <li>
          <a href="#proporție">Proporție</a>
        </li>
        <li>
          <a href="#ierarhie">Ierarhie</a>
        </li>
        <li>
          <a href="#spațiu-alb">Spațiu-alb</a>
        </li>
        <li>
          <a href="#unitate">Unitate</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#sfaturi-generale">Sfaturi Generale</a>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Despre Proiect

Acest repository repository a fost creat cu scopul de a te ajuta cu sfaturi sau resurse să creezi UI-uri fantastice.

* Ca și programator, timpul tău ar trebui să fie dedicat către programare și învățare. Nu toți ne dorim să fim designeri, dar uneori trebuie să lucrăm și pe partea vizuală a proiectelor.
* UI-ul (User Interface) nu reprezintă doar aspectul aplicației. UI-ul include UX-ul (User Experience). De fiecare dată când un utilizator interacționează cu aplicația ta, acesta ar trebui să fie deja comfortabil cu funcționalitățile ei și să știe ce face fiecare buton.
* Design-ul de UI nu este mereu combinații de font-uri, o alegere bună de palete de culori sau concepte și principii avansate de artă și design. Uneori e doar CONSISTENȚĂ.
* Încărcând UI-ul cu lucruri pe care nu le înțelegi sau nu știi cum să le combini este o practică rea. Consistența este ușor de obținut și va aduce rezultate imediate.
* Exact ca în programare, nu e nevoie să reinventezi roata. Folosește resursele disponibile pe Internet. Există o multitudine de resurse GRATUITE, gata să fie implementate în proiectele tale. De exemplu, putem utiliza icoane gratuite disponibile. Acestea pot să aibă diferite forme, de la simple imagini ```.svg``` / ```.png```, la elemente ```<i></i>``` HTML cu clase din librării precum <a href="https://fontawesome.com/icons">FontAwesome</a> sau <a href="https://icons.getbootstrap.com/">BootstrapIcons</a>, și până la componente ```JSX``` pe care le poți copia și adăuga direct în proiectele tale.

### La ce să te aștepți

Acest repository conține informații și resurse care să te ajute să creezi UI-uri pentru proiectele tale.

Având în vedere că nu am deloc experiență cu aplicații în afara web-ului, îți recomand să faci referire la sfaturi generale și îndrumări, și să le aplici ulterior în proiectele tale după bunul plac.

De exemplu, pentru UI-ul unei aplicații desktop, dacă dorești să adaugi o icoană unui buton, bănuiesc că ar trebui să salvezi imaginea icoanei, s-o adaugi în folder-ul proiectului tău și să folosești o metodă a unei clase ca să afișezi iconița în buton.

Poți să folosești Cuprinsul să navighezi către fiecare secțiune de interes.

Poți oricând să contribui cu orice crezi că lipsește sau ți se pare greșit, ca acest repository să ajute alți programatori sau studenți.

<p align="right">(<a href="#readme-top">înapoi la început</a>)</p>

<!-- BASIC DESIGN PRINCIPLES -->
## Principii de Bază în Design

### Contrast

Definit ca diferența dintre elementele dintr-un design care le face să iasă în evidență una față de cealaltă, contrastul joacă un rol important în vizibilitatea fiecărui element.

(Aproape) niciodată nu ar trebui să poziționezi un text de culoare albastră peste un fundal de un albastru puțin mai deschis. Această acțiune afectează lizibilitatea textului.

Firește, ai putea să aduci culoarea textului mai aproape de culoarea fundalului ca să sugerezi că textul este secundar, informațional, și nu joacă un rol important în transmiterea unui mesaj, dar chiar și în această situația, ar trebui să fie vizibil către utilizator.

### Proporție

Se referă la dimensiunea unui element în contrast cu alt element.

Utilizează conceptul de proporție în avantajul tău și definește elementele important, cum ar fi CTA-uri (Call to Action / Apel la acțiune), în relație cu forme și culori.

### Ierarhie

Plasăm elementele în consecința importanței lor. Ar trebui să asiguri o soluție vizuală pentru asta. Un simplu exemplu ar fi setarea dimensiunii unui titlu (```24px```) în contrast cu un paragraf (```12px```).

### Spațiu-Alb

Spațiul-alb este un element important în design. Putem defini spații goale pe o pagină, de o parte și de alta, și să menținem tot conținutul în centrul paginii. Pentru o postare dintr-un blog, această alegere îi permite utilizatorului să se concentreze pe text, cel mai important element dintr-un articol, și poate fi o soluție de a scurta lungimea liniilor de text, acestea fiind mai ușor de urmărit.

De exemplu, este mult mai ușor să citim rânduri care au o lungime de ```8-12``` cuvinte. Putem să urmărim cu ușurință care este următorul rând și să știm unde am rămas sau suntem în articol. E mult mai greu să citești un text care are rânduri de o lungime, ```24-28``` cuvinte.

Spațiul-alb poate fi și un separator foarte bun între elemente și grupări de elemente (Vezi <a href="#unitate">Unitate</a>).

### Unitate

Definirea grupurilor de elemente care sunt asociate unele cu altele îi oferă o structură solidă interfeței tale. De exemplu, mereu ar trebui să grupezi elementele importante legate de navigare în bara de navigare / navbar, sau, de obicei, grupezi butoanele de Autentificare / Înregistrare împreună, nu despărțite.

__

Acestea sunt 5 principii pe care le poți aplica ușor în proiectele tale pentru îmbunătățiri clare și rapide ale interfeței. În total există 12 principii, și dacă îți dorești să înveți mai multe despre ele, îți recomand să te documentezi mai mult despre subiect în timpul tău liber.

Toate aceste principii sunt:

1. Contrastul
2. Echilibrul
3. Accentuarea
4. Proporția
5. Ierarhia
6. Repetiția
7. Ritmul
8. Modelul
9. Spațiul-alb
10. Mișcarea
11. Varietatea
12. Unitatea

<p align="right">(<a href="#readme-top">înapoi la început</a>)</p>

<!-- GENERAL TIPS & TRICKS -->
## Sfaturi Generale

### Păstrează lucrurile simple și consistente

Acesta e cel mai important sfat pe care pot să îl ofer. Fii consistent în întreaga ta aplicație. Asta se referă la culoare, font-uri, dimensiuni, forme și multe altele.

### Creează un aspect implicit al aplicației tale

* Alege o culoare de fundal și ține-te de ea.
* Alege o dimensiune de text pentru fiecare element pe care crezi că-l vei avea pe pagină, dar limitează-te la o mână de elemente diferite. Paragrafele de text ar trebui să aibă o dimensiune de ```16px```. Aplică aceste dimensiuni consistent elementelor tale.
* Alege câteva culori pentru aplicația ta. Dacă ai o aplicație care are sau implementează un "brand", acest brand ar trebui să aibă un set de culori definite (de obicei, maxim 3). Pe lângă aceste culori, ar trebui să alegi culori în funcție de elementele aplicației tale. Dacă ai alerte informaționale, în funcție de tipul alertei, va trebui să alegi culori specifice (ex. roșu pentru pericol, portocaliu / galben pentru avertizări, verde pentru succes).
* Dacă ai un set de culori de brand pentru proiectul tău, alege nuanțele culorilor elementelor informaționale în funcție de culorile brand-ului. Dacă brand-ul are culori intense, puternice, va trebui să folosești nuanțe de roșu, verde și galben la fel de intense și de puternice ca și culorile brand-ului. Dacă brand-ul are culori pastel, jucăușe, va trebui să folosești culori pastel și pentru alerte.
* Pe lângă definirea unui set de culori pentru proiectul tău, ai grijă să fi consistent! Nu folosi o nuanță mai deschisă de roșu sau albastru pentru un element diferit, folosește exact aceeași culoare, exact același cod ```RGB / HEX```.
* Formele ar trebui să fie la fel de consistente ca și culorile. Dacă lucrezi pe o aplicați care implementează elemente cu colțuri rotunjite, menține valoarea de rotunjire consistentă pe toate elementele. Nu utiliza un border-radius de ```25px``` pe un buton și un border radius de ```20px``` pe containerul părinte. Menține aceleași valori.
* Utilizează același font peste tot. Ai nevoie de o viziune și înțelegere bună a tipografiei pentru a putea să combini font-uri. Folosește peste tot un singur tip de font. Definește importanța textului cu ajutorul dimensiunii, uneori a culorii, dar nu cu ajutorul unui font diferit. Tot textul pe care îl citești acum e afișat folosind ```Segoe UI```. Platforma GitHub își menține consistența și folosește același font pentru mesaje, text substituent în elemente input sau butoane. Singura excepție de la această consistență sunt blocurile de cod / markdown. Acestea sunt afișate utilizând un font monospace numit ```Consolas```.
* Pentru a oferi în continuare un exemplu de consistență de pe GitHub, tot ce este legat de pericol sau anularea unei acțiuni specifice este marcat cu ajutorul culorii roșie. Valoarea ```HEX``` a acestei culori este ```#DA3633```. Același albastru este folosit în toate link-urile și același verde este folosit pentru CTA-uri sau elemente care denotă confirmarea unei acțiuni.
* Consistența poate să fie regăsită și în dimensiune. Folosește aceeași dimensiune pentru butoane, același nivel de rotunjire pentru colțuri și diferențiază importanța lor prin culoare. The scopul aplicației tale este să atragă înregistrărea de utilizatori, care pot utiliza funcționalități gratuite ale aplicației tale, mai târziu fiind temptați de realizarea unei plăți pentru acces la mai multe funcționalități, vei defini butonul de ```Înregistrare``` ca și un CTA și vei avea butonul de ```Autentificare``` ca și o opțiune secundare lângă butonul de ```Autentificare```.
 
### Recomandări de font-uri

Sugerez explorarea platformei <a href="https://fonts.google.com/">Google Fonts</a> pentru a găsi font-uri care să vă satisfacă nevoile. Platforma le oferă utilizatorilor posibilitatea de a folosi ```import```-uri în stylesheet-uri sau elemente ```link```  de adăugat în ```head```-ul documentului ```HTML```. Poți, de asemenea, să descarci familii de font-uri sau grosimi specifice. Verifică licențele înainte de a utiliza font-uri.

Există și alte website-uri care să te ajute în găsirea unui font potrivit, dar recomand utilizarea platformei Google Fonts, având în vedere că oferă soluții pentru o implementare rapidă a font-urilor în proiectele tale.

Recomand implementarea a maxim ```2-3``` grosimi a unei familii de font-uri în proiectul tău. Utilizează grosimile Regular și Bold / Extra-Bold / Black.

Recomand, de asemenea, așa cum am menționat mai înainte, să mențineți consistență în tot proiectul. Folosiți aceeași dimensiune de font pentru paragrafe, aceeași dimensiune pentru butoane (de asemenea, aceeași înălțime / lățime / culoare a butonului, în funcție de cazul de utilizare).
__

##### Preferințe personale de font-uri

Aceste alegeri sunt subiective, fiind font-uri cu care sunt obișnuit și am folosit prin diferite proiecte web. Considerați utilizarea lor cu o oarecare indulgență.

* <a href="https://github.com/rsms/inter">Inter</a> - Un font minunat care a fost creat și proiectat special pentru ecranele dispozitivelor. E font-ul utilizat de mine în aproape orice proiect. Vezi și pagina <a href="https://fonts.google.com/specimen/Inter?query=inter">Google Fonts</a> a font-ului.
* <a href="https://www.cufonfonts.com/font/segoe-ui-4">Segoe UI</a> - Îl vezi chiar acum. GitHub utilizează implicit font-ul Segoe UI. Ar trebui să fie instalat și disponibil pe orice versiune de Windows începând cu Windows 7. Nu pot să garantez prezența font-ului pe distribuții de Linux sau pe MacOS, dar poți să-l descarci de oriunde gratuit.
* <a href="https://fonts.google.com/specimen/Montserrat?query=montserr">Montserrat</a> - Un font fantastic, iubit de multă lume.

Acestea sunt câteva dintre font-urile pe care le poți utiliza în proiectele tale. Simte-te liber să explorezi mai multe opțiuni. Toate acestea sunt font-uri sans-serif (fără serifă). Recomand să nu optezi pentru font-uri serif (cu serifă), decât dacă ai un motiv concret să faci asta.

Oricum, o alegere bună de font-uri cu serifă:

* <a href="https://fonts.google.com/specimen/Libre+Baskerville">Libre Baskerville</a> - De obicei o alegere foarte bună pentru postări de bloguri și corpurile articolelor, sau pentru simpla utilizare a titlurilor de tip display.
* <a href="https://befonts.com/butler-font.html">Butler</a> - Un typeface foarte bine proiectat și realizat utilizat pentru display sau grafică.

### Elemente vizuale

Oamenii sunt leneși. Toți urâm să gândim prea mult când încercăm să realizăm un lucru simplu. Ca și programator, trebuie să asiguri că elementele tale sunt ușor recognoscibile.

Poți să realizezi acest efect utilizând icoane. Adaugă icoane butoanelor tale ca să transmiți un mesaj mai bun utilizatorului. Până și o mică săgeată face diferența. Implementează icoane cu grijă, deoarece exagerând și supra-utilizând icoanele pot să-ți strice interfața și design-ul.

Dacă știi ce faci și ți-ai făcut un plan, utilizează ilustrații sau alte elemente grafice. Există o varietate de platforme care oferă ilustrații gratuite sau ieftine care pot să-ți imbunătățească un landing sau pot să transmită un mesaj mai puternic către utilizator. Sunt și super mișto.

### "Interfața asta arată bine" - Eu, către mine, sau tu, către tine

Experimentând cu diferite aplicații și versiuni de design, mereu ajung să fiu obișnuit cu UI-ul. Arată bine, dar oare este utilizabil? Uneori trebuie să-i lăsăm pe alții să testeze ceea ce noi am construit și ```*tulai maică*```, ne vor spune că e foarte rău. Le spun prietenilor sau familiei să se uite peste ceea ce am făcut. Uneori le ofer informații, alteori îi las să exploreze și să observ ce idei le vin. De cele mai multe ori ajung să observ lucruri la care nici nu m-am gândit.

Cel mai bun tester al aplicațiilor pe care le faci e cineva care nu a văzut aplicația ta înainte. Cere-le prietenilor feedback legat de design-ul tău. Dacă e posibil, lasă-i să-ți testeze aplicația, observă care e experiența lor utilizând aplicația. Spune-le să o "strice", poate ai anumite probleme de securitate sau codul tău pur și simplu nu face ceea ce vrei tu să facă.

### Oferă feedback utilizatorului

Poate crezi că are sens ca pagina articolelor postate de un utilizator să fie complet goală dacă acesta nu a postat nici un articol încă, nu? Păi, nu, nu ar trebui. Pune un substituent, un mesaj care să-i ofere utilizatorului informații suplimentare legate de ceea ce se întâmplă. Pagina e goală? Explică-i utilizatorului că e goală și de ce e goală. 

Nici un rezultat pentru căutare? "Ne cerem scuze, nu am găsit nimic pentru ```Cum să devii un programator bun și să câștigi 4 mii de euro pe lună```".

__

Uneori utilizatorul vrea toate datele legate de cei 905 Pokémoni disponibili, toate într-o singură pagină. Un request de genul acesta este destul de mare și va dura ceva timp până ce clientul primește toate datele.

O altă formă de feedback este când utilizatorul așteaptă să primească sau să vadă ceva anume. Dacă ai o operațiune foarte grea în aplicație care are un timp de executare îndelungat, oferă-i utilizatorului un feedback vizual ca să știe că aplicația ta nu s-a blocat sau stricat. O icoană de încărcare ar trebui să rezolva problema.

### Anticipează greșelile

Utilizatorii sunt *aproape* mereu oameni. Oamenii fac greșeli.

Încearcă să previi greșelile înainte ca acestea să se întâmple. Dezactivează butonul Submit cât utilizatorul completează un formular. După ce termină, activează-l.

Dar uneori nu putem preveni toate greșelile. Putem măcar să le anticipăm și să îi oferim utilizatorului un feedback ca să știe ce e greșit.

Dacă ei vor ca parola lor să fie ```parolafoartesigura123```, spune-le într-o manieră ușor de înțeles că tu ai configurat validarea formularului să accepte doar parole care conțin 12 caractere, conțin cel puțin o cifră, o majusculă și un simbol.

Afișează un container, sub câmpul de parolă, o eroare care menționează cele de mai sus.

<p align="right">(<a href="#readme-top">înapoi la început</a>)</p>
