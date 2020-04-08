# Algoritmi i strukture podataka

Slajdovi za predmet **Algoritmi i strukture podataka**. Studijski program
*Softversko inženjerstvo i informacione tehnologije*, prva godina, Univerzitet 
u Novom Sadu, Fakultet tehničkih nauka.

## Literatura

Materijal prati sadržaj knjige:

> Michael T. Goodrich, Roberto Tamassia, Michael H. Goldwasser. 
> *Data Structures and Algorithms in Python*. Wiley, 2013. ISBN 978-1118290279
> ([amazon](https://www.amazon.com/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275))


## Sadržaj

* `asp-00`: uvodne informacije o predmetu
* `asp-01`: analiza složenosti algoritama
* `asp-02`: rekurzija
* `asp-03`: uvod u objektno-orijentisano programiranje (Python)
* `asp-04`: nizovi
* `asp-05`: stek
* `asp-06`: red
* `asp-07`: lista
* `asp-08`: stablo
* `asp-09`: red sa prioritetom; heap; adaptivni red sa prioritetom
* `asp-10`: mapa; heš tabela; skip lista; skup
* `asp-11`: **stabla pretrage**: binarno stablo pretrage; AVL stablo; splay 
  stablo; (2,4)-stablo; crveno-crno stablo
* `asp-12`: **sortiranje i selekcija**: merge sort; quick sort; teorijski 
  limit brzine sortiranja; bucket sort; radix sort; quick select
* `asp-13`: **obrada teksta**: pretraga teksta (gruba sila; Boyer-Moore; 
  Knuth-Morris-Pratt); dinamičko programiranje; pohlepni algoritmi (Huffmanovo
  kodiranje; knapsack problem); trie stabla
* `asp-14`: **grafovi**: reprezentacije grafa; obilazak grafa (DFS, BFS); 
  usmereni graf (Floyd-Warshall, topološka analiza); težinski graf (Dijkstra,
  Bellman-Ford); minimalno pokrivajuće stablo (Prim-Jarnik, Kruskal)
* `asp-15`: upravljanje memorijom i B-stabla


## Prevođenje

Slajdovi su pripremljeni pomoću XeLaTeX sistema i 
[Beamer](https://en.wikipedia.org/wiki/Beamer_(LaTeX)) paketa. Za prevođenje 
koristiti:
```bash
xelatex -shell-escape asp-xx.tex
xelatex -shell-escape asp-xx.tex
```

Svi fajlovi se mogu prevesti odjednom pomoću (bash shell):
```bash
for i in asp-*.tex; do xelatex -shell-escape $i; done
for i in asp-*.tex; do xelatex -shell-escape $i; done
```

Rezultat prevođenja su fajlovi `asp-xx.pdf` koji predstavljaju gotove slajdove.
