---
layout: default
---

# [](#header-1)Belief functions and Epistemic Random Sets

* * *

**Uncertainty** arises in many circumstances:
* when data is noisy (e.g. photon counting data is Poisson distributed),
* when we need a simpler picture (e.g. a Brownian motion describes general statistical properties of the movement of a dust particle),
* when data is missing (e.g. the value of a feature is sometimes unknown for some examples in a dataset).

From the above examples, we see that there are two leading forms of uncertainty: randomness (aleatory uncertainty) and lack of knowledge (epistemic uncertainty).

**Probabilities** are an appealing mathematical model to grasp many aspects of uncertainty. When the nature of the problem is single-valued but the data we have access to is set-valued (or many-valued), other constructs are instrumental. 

>(As an example, consider a physical quantity _x_ that one wishes to determine but the sensing device one has can only indicate that _x_ belongs to some interval [_a_,_b_]. This measurement is imprecise in the sense that it is not single-valued. A sample of such measurements will contain different intervals owing to random fluctuations of the physical quantity and to measurement noise.)

In this case, one has to deal with of mix of the two forms of uncertainty and a workaround consists in hybridizing probability and set theories.

**Belief functions** are one such construct. In the following paragraphs, I explain that these functions can be built from probabilities in three different ways. In this regard, belief functions provide a framework which is a spin-off of probability theory and can be understood in well known probabilistic terms. This does not mean that they have to be understood in this way and other standpoints are also mentioned at the end of this note.

Regardless of the foundations of belief functions, these latter have a large expressive power which is essential in the quest for **artificial reasoning**, a domain of artificial intelligence that remains an uncharted territory. Indeed, intelligent beings can process a wide range of data and assumptions (single or set-valued) and make inferences from them. To artificially reproduce deductive mechanisms, an agile language is thus necessary.


## [](#header-2)The random set view

As in the above example, when an observation process is imprecise and produces set-valued measurements of an unknown point-valued and randomly fluctuating quantity that we wish to evaluate, we obtain an epistemic random set. This is in contrast with situations where the unknown is set-valued and the observation process is precise, in which case, we obtain an ontic random set. 

>(As an example of ontic random set, consider a that one wishes to track pedestrians in a video. The number and the positions of the pedestrians randomly varying over time. At a given time step, the set of their positions is a realization of an ontic random set.)

In the discrete case, random sets can be defined in the same way as usual random variables. In the continuous case, the probability that a random set is equal to a given deterministic _B_ is zero for any such set _B_ therefore we need to define another way to identify which sets are more likely to be observed as realizations of _S_. A workaround consists in examining how often _S_ hits _B_ or how often it is contained in _B_. This is exactly what the hitting and containment functionals are meant to grasp. These functionals fully characterize the random set _S_ and they both hold the same information as one can be computed from the other one and vice versa. A belief function is nothing but a containment functional of an epistemic random set.

<!-- 
Note that the belief function literature has mainly focused on the discrete case and has development a terminology of its own.
-->

## [](#header-2)The three-valued logic view

When the truth or the falsity of a proposition cannot be (fully) determined in light of evidence, one can introduce a third epistemic state: the _don't know_ state. 

State      | known to be true | known to be false | don't know |
-----------|:-----------------|:------------------|:-----------|
Probability|_u_               | _v_               | _w_        |

Probabilities can be distributed on each state as usual: _u + v + w = 1_. By building upon this idea, we see that probability triplets for each proposition must follow some assignment rules. In particular, if some event is know to be true with probability _u_, then the complement of this event is known to be false with the same probability.

> An equivalent representation of the same information are given by (epistemic) **random sets**. The probability that that a given set contains the random set is _u_. The probability that the random set intersects a given set is _u+w_.



## [](#header-2)The probability bound view

Following the above notations, we see that the probability _p(A)_ of event _A_ can be bracketed by _u_ and _u+w_. In this case, the function that maps each event to its probability lower bound is a belief function. In general, not all probability lower bounds are belief functions and belong to a more general framework known as **imprecise probabilities** that relies on capacity theory and Choquet integrals. A belief function is actually an infinite monotone lower probability.

The set of inequalities _u \< p(A) \< u+w_ also defines a region of the space of probability distribution. Thus, belief functions are also in correspondence with "feasible sets of probability distributions" known as credal sets.

<!--
> Other related frameworks are:
> Fiducial inference, Robust Bayesian analysis, Lower previsions. 
-->

## [](#header-2)The non-probabilistic view

Although a number of works were pre-existing, the paper of A. P. Dempster from 1967 is considered to be the first characterization of belief functions. Dempster supervised the PhD of G. Shafer who further developed Dempster's ideas in his _Allocation of Probability_ which was defended in 1973. These works are mainly lying within the framework of probability theory.

In 1976, Shafer published a book in which he introduces belief function as part of a theory of their own. By building upon a different set of axioms from Kolmogorov, belief functions can be defined without probabilistic foundations. Shafer entitled his book _a mathematical theory of evidence_, which is why belief functions seen as a theory are often referred as evidence theory or Dempster-Shafer theory. In this theory, an operator on belief functions called Dempster's rule of combination plays a central role. It can be regarded as a generalization of conditioning and set intersection. Contributions tagged as Dempster-Shafer theoretic are thus meant to rely on this operator. But contributions with belief functions as key-words can rely on any of the aforementioned interpretations.


> Dempster, A. P. (1967). Upper and lower probabilities induced by a multiple valued mapping. Annals of Mathematical Satistics, 38(2):325–339.
> Shafer, G. (1973). Allocations of Probability: A Theory of Partial Belief. Ph.D. Dissertation, Statistics, Princeton University
> Shafer, G. (1976). A Mathematical Theory of Evidence. Princeton University press, Princeton (NJ), USA. 


Copyright © John Klein 2019


