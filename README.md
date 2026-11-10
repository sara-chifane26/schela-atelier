# Schela · Atelier

Unealtă pentru documentația tehnică a lucrărilor de construcții și instalații: inventarul dosarului, duplicate, cartea tehnică pe dosare, lipsuri, cereri de documente către executanți și furnizori, opis și borderouri.

**Deschide aplicația:** https://sara-chifane26.github.io/schela-atelier/

## Confidențialitate

Aplicația rulează **doar în browserul tău**. Fișierele pe care le alegi sunt citite local (denumire, mărime, amprentă) și **nu sunt trimise nicăieri** — site-ul nu are server și nici bază de date. Proiectul se salvează în browser și, la cerere, într-un fișier `.json` pe calculatorul tău.

## Exemplu

Pe pagina de intrare, butonul **Deschide exemplul** adaugă în listă o lucrare demonstrativă cu **date fictive**: fibră optică pe LEA 110 kV, la Instalații electrice, cu câteva documente-exemplu (2 tronsoane, 2 balize, 2 prize de pământ) și situația cărții tehnice pe dosare; titlurile PV-urilor sunt doar exemple.

## Ce face

Pagina de intrare are opt chenare, câte unul pe domeniu: **construcții civile, drumuri, instalații electrice, termice, sanitare, gaze, rețele edilitare, HVAC**. Fiecare duce la aceeași structură, de la proiect la cartea tehnică. Domeniul vine din chenar; la instalații electrice alegi tipul lucrării o singură dată, când pornești lucrarea (clădiri, rețele LEA/LES, LEA cu fibră optică, fotovoltaic, paratrăsnet, IDSAI, supraveghere video, antiefracție, control acces). Lucrările mixte pot avea mai multe specialități. La **Proiect** treci persoanele o singură dată, cu domeniile de autorizare ISC ale dirigintelui și ce acoperă din lucrare, și stadiul lucrării: în pagina domeniului lucrările apar la „În derulare” sau „Finalizate” (după recepție).

1. **Inventar** — documentele sunt împărțite automat pe rubrici, fiecare cu chenarul ei (avize, PV-uri de execuție, probe, documente de calitate, dispoziții de șantier etc.); încarci folderul lucrării; fiecare fișier trece prin verificarea la intrare (copii identice respinse, versiuni noi semnalate, lipsuri rezolvate automat).
2. **Duplicate** — alegi versiunea în vigoare.
3. **Carte tehnică** — fiecare dosar (A1 … D1) are chenarul lui; în pagina dosarului vezi documentele necesare și starea lor, alegi fișierul de mână, marchezi „nu se aplică” sau ceri documentul lipsă. Lista beneficiarului se încarcă ca PDF, Word, Excel sau poză. Completezi parametrii fiecărei specialități; aplicația reunește documentele așteptate pe dosare A–D după HG 343/2017 (Anexa 6), cu piesele comune o singură dată, le caută în inventar și tipărește borderourile. Documentele cerute în plus de beneficiar se adaugă într-un câmp separat. În Chrome sau Edge, aplicația poate aranja copiile fișierelor în foldere Dosar A1 … D1, numerotate ca în borderou.
4. **Materiale** — lista materialelor principale, cu documentul de calitate al fiecăruia și confirmarea că acesta corespunde materialului livrat.
5. **Execuție** — fazele determinante cu termenul de convocare ISC și model de convocare, semnăturile pe PV-uri, registrul dispozițiilor de șantier.
6. **Conformitate** — verifică dosarul față de legislație (HG 343/2017, Legea 10/1995, Ordinul MDRAP 1370/2014 pentru controlul ISC) și față de normativele fiecărui domeniu (I 7, I 9, I 13, I 5, NTPEE, NP 133, P 118/3, HG 301/2012 etc.) și semnalează, pe faze, documentele lipsă cu temeiul legal.
7. **Lipsuri** și **Cereri** — ce lipsește, de la cine, cu termene și reamintiri.
8. **Rezultate** — statistici, opis (tipărire / PDF), exporturi CSV.

**Boloboc** — butonul din colțul din dreapta jos: răspunde la întrebări despre dosar („ce lipsește?”, „cine întârzie?”, „ce fac acum?”), despre folosirea aplicației și despre noțiunile de specialitate (faze determinante, lucrări ascunse, as built, recepție), cu temeiul legal. Funcționează fără AI și fără internet: nimic nu pleacă din pagină.

Documentele se adaugă cu butonul, trăgându-le (fișiere ori foldere întregi) în pagină sau, în Chrome și Edge, din **folderul lucrării legat** o singură dată (și de pe server, mapat ca disc): „Verifică folderul” aduce doar fișierele noi.

Totul se citește local, în browser:
- din PDF și Word (.docx și .doc vechi) — începutul textului: numărul și data PV-urilor și ale dispozițiilor, denumirea produsului și producătorul din certificate și declarațiile de performanță;
- documentele de calitate sunt recunoscute în **română, engleză, germană, franceză, spaniolă și turcă**: aplicația arată tipul documentului în română și limba lui (de exemplu „Leistungserklärung” = declarație de performanță, în germană);
- din scanuri și poze — prin OCR (Tesseract), la cerere: întâi în română și engleză, apoi, dacă documentul pare în germană, franceză, spaniolă sau turcă, din nou în limba lui;
- din PDF-urile semnate electronic — numele semnatarilor, care bifează singure semnăturile pe PV-uri.

Bibliotecile pdf.js și Tesseract se încarcă de pe cdnjs / jsDelivr la prima folosire; documentele nu pleacă din calculator.
