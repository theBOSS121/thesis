Hours: 13h

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

The inversion number is the number of crossings in the arrow diagram of the permutation

Kendall tau distance or bubble sort distance

inversion vector or Lehmer code.


An inversion of f is an ordered pair (ai, aj), where i < j
but ai > aj. Equivalently, (x, y) is an inversion
if and only if x > y and f^(-1)(x) < f^(-1)(y)










































































Ime teme:
Metoda za avtomatski izračun značilnic primernih za kalibracijo večmodalnih slik. Recimo RGB in Termalnih (za podatkovno zbirko uporabimo našo iz FE). Izhaja se iz SuperGLUE (https://github.com/magicleap/SuperGluePretrainedNetwork). Pregleda se literaturo, sicer pa izvede učenje detektorja točk na eni modalnosti in ločeno na drugi. Potem pa učenje feature extractorja, da SuperGLUE funkcionira.

"Metoda za avtomatski izračun značilnic primernih za kalibracijo večmodalnih RGB in Termalnih slik za ujemanje s SUPERGLUE".

Mentor: dr. Matej Kristan
Somentor: dr. Janez Perša


TODO:
clanek: https://arxiv.org/abs/1911.11763
SUPERGLUE: https://psarlin.com/superglue/
hloc: https://github.com/cvg/Hierarchical-Localization/
Pytorch
python
deep learning
http://cs231n.stanford.edu/
http://cs231n.github.io/

→ Graph Neural Networks, Attention, Optimal Transport, Sinkhorn Algorithm
chain rule for backpropagation

Graph Neural Network
Optimal Matching layer


DONE:
python begginer tutorial
python intermediate tutorial
stanford cs231n 2017 youtube playlist
3b1b neural network playlist