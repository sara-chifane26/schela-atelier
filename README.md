# Schela · Atelier

Unealtă pentru documentația tehnică a lucrărilor de construcții și instalații: inventarul dosarului, duplicate, cartea tehnică pe dosare, lipsuri, cereri de documente către executanți și furnizori, opis și borderouri.

**Deschide aplicația:** https://sara-chifane26.github.io/schela-atelier/

## Confidențialitate

Aplicația rulează **doar în browserul tău**. Fișierele pe care le alegi sunt citite local (denumire, mărime, amprentă) și **nu sunt trimise nicăieri** — site-ul nu are server și nici bază de date. Proiectul se salvează în browser și, la cerere, într-un fișier `.json` pe calculatorul tău.

## Exemplu

Pe pagina de intrare, butonul **Deschide exemplul** adaugă în listă o lucrare demonstrativă cu **date fictive**: fibră optică pe LEA 110 kV, la Instalații electrice, cu 103 documente și situația cărții tehnice pe dosare.

## Ce face

Pagina de intrare are opt chenare, câte unul pe domeniu: **construcții civile, drumuri, instalații electrice, termice, sanitare, gaze, rețele edilitare, HVAC**. Fiecare duce la aceeași structură, de la proiect la cartea tehnică. O lucrare poate avea mai multe domenii, iar la instalații electrice alegi tipurile (clădiri, rețele LEA/LES, LEA cu fibră optică, fotovoltaic, paratrăsnet, IDSAI, supraveghere video, antiefracție, control acces). La **Proiect** treci persoanele o singură dată, cu domeniile pe care le acoperă.

1. **Inventar** — încarci folderul lucrării; fiecare fișier trece prin verificarea la intrare (copii identice respinse, versiuni noi semnalate, lipsuri rezolvate automat).
2. **Duplicate** — alegi versiunea în vigoare.
3. **Carte tehnică** — completezi parametrii fiecărei specialități; aplicația reunește documentele așteptate pe dosare A–D după HG 343/2017 (Anexa 6), cu piesele comune o singură dată, le caută în inventar și tipărește borderourile. Documentele cerute în plus de beneficiar se adaugă într-un câmp separat.
4. **Conformitate** — verifică dosarul față de legislație (HG 343/2017, Legea 10/1995, Ordinul MDRAP 1370/2014 pentru controlul ISC) și față de normativele fiecărui domeniu (I 7, I 9, I 13, I 5, NTPEE, NP 133, P 118/3, HG 301/2012 etc.) și semnalează, pe faze, documentele lipsă cu temeiul legal.
5. **Lipsuri** și **Cereri** — ce lipsește, de la cine, cu termene și reamintiri.
6. **Rezultate** — statistici, opis (tipărire / PDF), exporturi CSV.

**Boloboc** — butonul din colțul din dreapta jos: răspunde la întrebări despre dosar („ce lipsește?”, „cine întârzie?”, „ce fac acum?”), despre folosirea aplicației și despre noțiunile de specialitate (faze determinante, lucrări ascunse, as built, recepție), cu temeiul legal. Funcționează fără AI și fără internet: nimic nu pleacă din pagină.
