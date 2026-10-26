# STIRISPORT.EU — Fotbal fără pauză

Versiune tehnică și editorială revizuită: 26 octombrie 2026.

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
