---
layout: post
title: "Hill-Robertson Effects"
modified:
categories: evolution
excerpt: "A very short introduction to Hill Robertson Effects"
tags: [hill robertson effects, evolution]
image:
  feature: dnaseq.jpg
date: 2015-10-15T19:06:40+02:00
comments: true
---

{% include _toc.html %}

> Hill-Robertson effects are interference between two locus under selection. When
> recombination is weak, selection on the two locus interfere. Selection is less
> efficient than when it acts on two independent locus.

Consider *A* and *B*, two moderately advantageous allele, in different
population. They are under positive or directional selection. If recombination
is weak, an optimal *AB* combination can never appear. *A* and *B* interfere
with each other.

Those are the typical Hill-Robertson effects, as described by Hill and Robertson
in 1966. They have been described under other declination since.

## Selective Sweep

Consider *A*, a strongly advantageous allele, and *b* a weakly deleterious
allele. *b* is linked to *A*{% sidenote "189" "They are in *linkage desequilibrium*" %}. The advantageous effects of *A* leads to its
invasion in the population. It can even lead to a point of fixation. It is thus
a selective sweep of *A*.

But *b* is linked to *A*. *b* will also invade the population, even if it is
deleterious. This is a case of "genetic hitch-hiking"{% sidenote "751" "As coined by John Maynard Smith" %}. 

## Background selection

It is the opposite case of selective sweep interference. Consider now *B*, a
strongly deleterious allele, and *a* a weakly advantageous allele. *a* is linked
to *B*. The deleterious effects of *B* lead to the extinction of *B* carrying
individuals.

But *a* is linked to *B*. *a* will disappear from the population, even if it is
advantageous. This is a case of background selection. All polymorphism linked to
a strongly deleterious allele is purged. 

## Muller's Ratchet

> Muller's ratchet was first described in 1932.

It happens in clonal species, with small population sizes. A population carrying
no deleterious mutation is a population subgroup. When the first deleterious
mutation appears, the population ratchets up on the mutational burden. Since
recombination is weak, given the small population size, this mutation has no
chance to be cured. When further deleterious mutation occurs, population
degenerate. Its fitness irresistibly drops down, to the point of extinction.

## Conclusion

Hill-Robertson effects only occurs when recombination is weaker than mutation.
Polymorphism decreases and selection efficacy decreases too. One must consider
selection intensity, mutation and recombination respective rates. The size of
the genomic window affected depends on those three parameters : if recombination
is weak and selection strong, genome can be affected on a large scale. 

Hill-Robertson effects can explain counter intuitive observations. The spread of
deleterious allele can be explained by genomic interference, as is the case with
cystic fibrosis.
