# thesis

permutacije
predstavitve permutacij
grupa
simetricna grupa
cayleyev izrek
razlicni nacini predstavitve inverzij
zanimivosti o inverzijah
rodovna funkcija
permutacijski grafi
karektarizacija permutacijskih grafov
delne urejenost permutacij

TODO:
primeri
slike
glavni primer iz karakterizacije in construkcije permutacijskih grafov



links:
https://en.wikipedia.org/wiki/Inversion_(discrete_mathematics)
https://en.wikipedia.org/wiki/Permutation
https://en.wikipedia.org/wiki/Permutation_graph
https://en.wikipedia.org/wiki/Permutation_group#Transpositions,_simple_transpositions,_inversions_and_sorting
https://en.wikipedia.org/wiki/Parity_of_a_permutation
https://oeis.org/A008302 (polynomial, recursive relation)
https://www.youtube.com/watch?v=6WjnRyYLmM4&list=PLnQX-jgAF5pQS2GUFCsatSyZkSH7e8UM8&index=17 (permutation diagram points in a square and much more) 

Papers on graphs of inversions of permutations:
Characterization and Construction of Permutation Graphs:
https://pdfs.semanticscholar.org/6bbc/d1cbc4495e8d7d95d8bca07a702172c6aaf1.pdf
Permutation graphs and the weak Bruhat order*:
https://adam-journal.eu/index.php/ADAM/article/view/1536/1498
On graphs associated to sets of rankings / Comparing rankings by means of competitivity
graphs: structural properties and computation (same authors):
https://www.sciencedirect.com/science/article/pii/S0377042715001557?ref=pdf_download&fr=RR-2&rr=818f1d58fbfc5a59
https://arxiv.org/pdf/1310.6921.pdf

maybe later:
https://www.sciencedirect.com/science/article/pii/S0166218X87800033?ref=cra_js_challenge&fr=RR-1
https://arxiv.org/pdf/1709.06979.pdf

Inversion number can be thought of as a measure of how “out of order” a
permutation is.

We can use a polynomial to keep track of how many permutations of a
given size 𝑛 have a certain inversion number. Let’s call this the “inversion
number polynomial.”
Each permutation’s contribution to this polynomial will be 𝑥 raised to the
power of that permutation’s inversion number.
To form the whole polynomial, we add up all these powers of x
n=2: 𝑥 + 1
n=3: 𝑥^3 + 2𝑥^2 + 2𝑥 + 1 = (𝑥^2 + 𝑥 + 1)(𝑥 + 1)
n=4: 𝑥^6 + 3𝑥^5 + 5𝑥^4 + 6𝑥^3 + 5𝑥^2 + 3𝑥 + 1 = (𝑥^3 + 𝑥^2 + 𝑥 + 1)(𝑥^2 + 𝑥 + 1)(𝑥 + 1)
general n: (𝑥^𝑛−1 + 𝑥^𝑛−2 + ⋯ + 𝑥 + 1)(𝑥^𝑛−2 + 𝑥^𝑛−2 + ⋯ + 𝑥 + 1) ⋯ (𝑥^2 + 𝑥 + 1)(𝑥 + 1)

https://cs.uwaterloo.ca/journals/JIS/VOL4/MARGOLIUS/inversions.pdf

The inversion number is the number of crossings in the arrow diagram of the permutation

Kendall tau distance or bubble sort distance

inversion vector or Lehmer code.


An inversion of f is an ordered pair (ai, aj), where i < j
but ai > aj. Equivalently, (x, y) is an inversion
if and only if x > y and f^(-1)(x) < f^(-1)(y)


41