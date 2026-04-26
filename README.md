# SA-Project
#  Analiza Performanței Algoritmilor de Sortare

##  Descriere

Acest proiect, realizat în limbajul **Python**, are ca scop analizarea și compararea performanței mai multor algoritmi clasici de sortare.

Aplicația generează liste de diferite tipuri și măsoară timpul de execuție pentru fiecare algoritm, oferind o perspectivă practică asupra complexității acestora.

---

##  Obiective

- Implementarea algoritmilor de sortare fundamentali
- Compararea performanței acestora în funcție de tipul datelor
- Evidențierea diferențelor între cazurile:
  - favorabile
  - nefavorabile
  - medii

---

##  Algoritmi implementați

###  Bubble Sort
- Compară elementele adiacente
- Complexitate:
  - Best: O(n)
  - Average/Worst: O(n²)

###  Selection Sort
- Selectează minimul la fiecare pas
- Complexitate:
  - Toate cazurile: O(n²)

###  Insertion Sort
- Inserează elementele în poziția corectă
- Complexitate:
  - Best: O(n)
  - Worst: O(n²)

###  Quick Sort
- Divide et impera
- Alege pivot și împarte lista
- Complexitate:
  - Average: O(n log n)
  - Worst: O(n²)

---

##  Tipuri de date testate

Programul testează algoritmii pe mai multe tipuri de liste:

-  **Listă aleatoare** – valori generate random
-  **Listă sortată** – caz favorabil pentru unii algoritmi
-  **Listă sortată invers** – caz nefavorabil
-  **Listă aproape sortată** – mici perturbări într-o listă ordonată

---

##  Măsurarea performanței

Timpul de execuție este măsurat folosind modulul:

```python
time.time()
