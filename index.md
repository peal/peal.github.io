# PEAL: Permutation groups and algorithms

**PEAL** is an organisation that hosts a collection of tools for computing with
permutation groups.

Here we list the people that have been directly involved in PEAL so far,
our projects within PEAL, and our associated written publications.


## People

Each of the following projects has its own collection of authors, maintainers, and contributors.
Here, we simply list the union of these people,
i.e. everyone who has directly contributed to PEAL’s tools, in one way or another.
So far, we have all come to be associated with PEAL by our connections with the [AI Research Group](https://airg.cs.st-andrews.ac.uk) at the [School of Computer Science](https://www.st-andrews.ac.uk/computer-science) of the [University of St Andrews](https://www.st-andrews.ac.uk).

* [Christopher Jefferson](https://caj.host.cs.st-andrews.ac.uk)
* [Wilf A. Wilson](https://wilf.me)
* [Ruth Hoffmann](https://rh347.host.cs.st-andrews.ac.uk)
* Mun See Chang
* Ewan Gilligan
* [Markus Pfeiffer](https://markusp.morphism.de)
* Giacomo Fenzi


## Projects


### ★ Vole

[Vole](https://peal.github.io/vole)
is a GAP package written in Rust
that aims to provide a high-performance implementation of the graph backtracking algorithm of the paper
“[Permutation group algorithms based on directed graphs](https://doi.org/10.1016/j.jalgebra.2021.06.015)”.
Vole also implements new tools for canonising in arbitrary finite permutation groups, whose underlying theory is in preparation for publication.


### ★ GraphBacktracking

[GraphBacktracking](https://peal.github.io/GraphBacktracking)
is a GAP package that provides a proof-of-concept implementation of the 
graph backtracking algorithm of the paper
“[Permutation group algorithms based on directed graphs](https://doi.org/10.1016/j.jalgebra.2021.06.015)”.  The GraphBacktracking package was used for the experiments described in that paper, and is not intended to have high performance.


### ★ BacktrackKit

[BacktrackKit](https://peal.github.io/BacktrackKit)
is a GAP package that aims to provide a reference implementation of the partition backtracking algorithm of [Jeffrey Leon](https://doi.org/10.1016/S0747-7171(08)80103-4). It is not intended to have high performance.


### ★ DirectDisjointProdDecomposition

[DirectDisjointProdDecomposition](https://github.com/peal/DisjointDirectProdDecomposition)
is a collection of GAP code that includes an implementation of the algorithm described in the paper “[Disjoint direct product decompositions of permutation groups](https://doi.org/10.1016/j.jsc.2021.04.003)”, along with the code that was used for the experiments in that paper.
This algorithm decomposes a permutation group that is a direct product,
whose factors act on disjoint sets of points, into those factors.

DirectDisjointProdDecomposition was created by Mun See Chang and Christopher Jefferson.


### ★ GrpLib

[GrpLib](https://peal.github.io/grplib) is a library of problems in computational group theory, along with a library of families of permutation groups. These groups are provided in a format that allows them to be easily used in computations.

GrpLib is maintained by Ruth Hoffmann and Christopher Jefferson.


## Associated PEAL publications

* Mun See Chang and Christopher Jefferson, **“Disjoint direct product decompositions of permutation groups”**, _Journal of Symbolic Computation_ **108** (2022) 1–16.
    * DOI: [10.1016/j.jsc.2021.04.003](https://doi.org/10.1016/j.jsc.2021.04.003)
    * arXiv: [2004.11618](https://arxiv.org/abs/2004.11618)


* Christopher Jefferson, Markus Pfeiffer, Rebecca Waldecker, and Wilf A. Wilson, **“Permutation group algorithms based on directed graphs”**, _Journal of Algebra_ **585** (2021) 723–758.
    * DOI: [10.1016/j.jalgebra.2021.06.015](https://doi.org/10.1016/j.jalgebra.2021.06.015)
    * arXiv: [2106.13132](https://arxiv.org/abs/2106.13132)
        * An earlier, extended version of this paper is available at arXiv: [1911.04783](https://arxiv.org/abs/1911.04783).
