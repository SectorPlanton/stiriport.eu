# STIRISPORT.EU — Fotbal fără pauză

Versiune tehnică revizuită: 7 noiembrie 2026.

## Publicare pe GitHub Pages
1. Copiază conținutul acestui director în rădăcina repository-ului GitHub.
2. În Settings → Pages, selectează `Deploy from a branch`, `main`, folderul `/ (root)`.
3. Păstrează fișierul `CNAME` și configurează DNS-ul domeniului `stirisport.eu` conform instrucțiunilor GitHub Pages.
4. După publicare, testează HTTPS, toate paginile și formularul/canalele reale de contact.

## Structură
- `index.html` — homepage
- pagini de competiții: SuperLiga, Naționala, Premier League, La Liga, Bundesliga, Serie A, Champions League, Europa League, Conference League, Cupa Mondială, EURO și Liga Națiunilor
- `rezultate.html`, `arhiva.html`, articole statice în `articole/<id>.html`; `article.html?id=...` rămâne fallback
- `betting.html`, `casino-bonusuri.html`, `magazin.html`, `afiliere.html`
- `confidentialitate.html`, `cookies.html`, `termeni.html`, `contact.html`
- `js/data.js` — date editoriale și snapshot-uri; `js/app.js` — randare, căutare, navigare și preferințe; `articole/` — pagini individuale indexabile pentru articole

## Actualizare editorială obligatorie
Ediția editorială din 26 octombrie 2026 include o sinteză a etapei a 13-a din SuperLiga, avancronica Sepsi – Universitatea Craiova și un ghid al programului zilei. Materialele noi trimit la surse publice; rezultatele și programul trebuie reverificate înainte de actualizări ulterioare. Nu modifica datele articolelor vechi pentru a le prezenta ca noi. Scorurile live nu sunt conectate la un furnizor de date, iar cotele și ofertele vechi nu sunt afișate drept actuale; cota zilei și biletul zilei rămân nepublicate până la verificarea unei piețe actuale.

Pentru fiecare articol, actualizează `ARTICLES` în `js/data.js` cu titlu, rezumat, dată, categorie, URL-ul sursei și text propriu verificat. Arhiva folosește data articolului.

## Monetizare
- Spațiile publicitare sunt demonstrative și sunt marcate neactive; nu există coduri AdSense sau analytics active în această versiune.
- Linkurile afiliate din `affiliate.js` rămân goale până când există URL-uri de tracking oficiale și conturile sunt aprobate.
- Ofertele de pariuri/casino nu trebuie publicate ca active fără verificarea termenilor și a statutului operatorului în România.

## Legal și confidențialitate — înainte de lansare
Paginile sunt șabloane informative și nu substituie consultanța juridică. Proprietarul trebuie să completeze datele reale de identificare și contact în paginile relevante și să verifice conformitatea cu situația reală a operatorului. Nu activa Google Analytics, AdSense, pixeli sau alte servicii opționale fără actualizarea politicilor și implementarea consimțământului adecvat.

## SEO
`robots.txt` și `sitemap.xml` includ paginile statice. După publicare, verifică domeniul și sitemap-ul în Google Search Console și inspectează erorile de indexare.


## Jurnal editorial — 26 octombrie 2026
- Adăugate trei articole datate 26 octombrie 2026: sinteza etapei 13 din SuperLiga, avancronica Sepsi OSK – Universitatea Craiova și programul fotbalistic al zilei.
- Actualizată pagina `rezultate.html` cu rezultatele confirmate de LPF și următorul meci programat.
- Dezactivate cotele și selecțiile istorice din secțiunea betting; acestea nu sunt prezentate ca actuale.
- Înlocuită lista de bonusuri casino active cu un ghid de verificare, până la confirmarea ofertelor și a statutului operatorilor.
- Scorurile live nu sunt conectate; nu sunt prezentate ca live.


## Corecție editorială — 26 octombrie 2026
- Corectată inversarea echipelor din titlul și textul știrii despre derby: **FCSB – Rapid 4–1 (0–1 la pauză)**, nu victorie Rapid.
- Adăugate în știre minutele marcatorilor conform relatărilor consultate: Stojilkovic 11; Muhar 58; Boutoutaou 69 și 81; João Paulo 79.
- Corectat teaserul de pe pagina Rezultate. Pentru știrile viitoare, publicarea trebuie să aștepte confirmarea rezultatului din sursă oficială sau din cel puțin două surse editoriale credibile.


## Audit editorial — 26 octombrie 2026
- Lista `ARTICLES` este ordonată după data publicării, în ordine descrescătoare, pentru a evita afișarea materialelor vechi înaintea celor noi.
- Banda de știri afișează maximum 12 titluri din lista deja sortată, nu 18 titluri preluate din ordinea inițială a fișierului.
- Acest pas este o îmbunătățire a ordinii afișării, nu o confirmare independentă a tuturor afirmațiilor istorice. Scorurile, marcatorii și programul trebuie verificate la surse oficiale înainte de republicare.


## Identitate vizuală (26 octombrie 2026)
Logo-ul bazat pe profilul TikTok @stirisport.eu a fost integrat în assets/stirisport-logo.png și în pictogramele site-ului. Profil TikTok: https://www.tiktok.com/@stirisport.eu


## Studio Social
Deschide `studio-social.html` în browser (sau prin Live Server) pentru a crea vizualuri verticale PNG 1080×1920 pentru TikTok/Reels. Completează numai informații verificate; editorul nu verifică automat știrile.


## Actualizare tehnică — 2 noiembrie 2026
- Integrate în `ARTICLES` cele 18 articole statice care existau în `articole/`, dar lipseau din fluxul dinamic. Acestea devin disponibile în căutare, arhivă, homepage (în funcție de dată) și paginile de competiții.
- Data ediției de pe homepage este afișată dinamic, folosind data locală a vizitatorului.
- Sitemap-ul a fost regenerat din fișierele HTML existente; nu au fost inventate valori `lastmod`.
- Verificarea Search Console rămâne necesară după publicare. Răspunsul public HTTP 200 și `application/xml` confirmă livrarea sitemap-ului, dar nu explică singure eroarea de procesare din Google.


## Actualizare editorială — 7 noiembrie 2026
- Adăugate sinteze actualizate pentru SuperLiga, Premier League, LaLiga, Bundesliga, Serie A și competițiile UEFA.
- Adăugat material pentru Marele Premiu de Formula 1 de la São Paulo și o secțiune „Alte sporturi”.
- Pagina Rezultate reflectă rezultatele confirmate și programul 7–9 noiembrie 2026; nu există conexiune la scoruri live.
- Betting este exclusiv pre-match. Nu sunt publicate cote sau selecții în această ediție, deoarece comparația multi-operator nu a putut fi verificată complet.
- Eliminat scriptul AdSense încărcat înainte de alegerea cookies. Publicitatea rămâne neactivă până la implementarea și testarea unei soluții de consimțământ conforme.
- Corectate datele NewsArticle JSON-LD care indicau un articol greșit pe 14 pagini.
- Corectată și completată sinteza istorică a etapei a 14-a din SuperLiga pe baza rezultatelor finale LPF.
