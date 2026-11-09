# Schela · Atelier

Unealtă pentru documentația tehnică a lucrărilor de construcții și instalații: inventarul dosarului, duplicate, cartea tehnică pe dosare, lipsuri, cereri de documente către executanți și furnizori, opis și borderouri.

**Deschide aplicația:** https://sara-chifane26.github.io/schela-atelier/

## Confidențialitate

Aplicația rulează **doar în browserul tău**. Fișierele pe care le alegi sunt citite local (denumire, mărime, amprentă) și **nu sunt trimise nicăieri** — site-ul nu are server și nici bază de date. Proiectul se salvează în browser și, la cerere, într-un fișier `.json` pe calculatorul tău.

## Exemplu

În pagina **Proiect**, butonul **Deschide exemplul** încarcă un proiect demonstrativ cu **date fictive**: o lucrare de fibră optică pe LEA 110 kV, cu 89 de documente și situația cărții tehnice pe dosare.

## Ce face

1. **Inventar** — încarci folderul lucrării; fiecare fișier trece prin verificarea la intrare (copii identice respinse, versiuni noi semnalate, lipsuri rezolvate automat).
2. **Duplicate** — alegi versiunea în vigoare.
3. **Carte tehnică** — din parametrii lucrării se generează documentele așteptate pe dosare; aplicația le caută în inventar și tipărește borderourile.
4. **Conformitate** — verifică dosarul față de legislație (HG 343/2017, Legea 10/1995, Ordinul MDRAP 1370/2014 pentru controlul ISC) și semnalează, pe faze, documentele lipsă cu temeiul legal.
5. **Lipsuri** și **Cereri** — ce lipsește, de la cine, cu termene și reamintiri.
6. **Rezultate** — statistici, opis (tipărire / PDF), exporturi CSV.
