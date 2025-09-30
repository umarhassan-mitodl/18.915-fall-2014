---
content_type: page
description: In this section, the instructor and student share their reading response
  correspondence for September.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Reading Responses
parent_type: CourseSection
parent_uid: 674cd4bf-8f3b-2929-b29c-0e8c85131638
title: September
uid: f099e4bc-dad3-1d7f-c8c6-e204a63f8de1
---

### 4 Sep

_Response to:_ {{% resource_link e7fadd2e-74e9-906c-812c-22b196f54bf6 "_Steenrod Operations (PDF - 1.7MB)_" %}}

Dear Professor Miller,

Here is my response:

Before reading your notes I had seen the definition of the Steenrod squares given in Mosher-Tangora "Cohomology Operations and Applications in Homotopy Theory". This approach makes more concerted use of the cell structure of B\_(Z/2Z) = RP^\\infty and E\_(Z/2Z) = S^\\infty and defines the Sq^i in terms of cup\_i products on integral cochains.

I think that I understand the more geometric construction based upon the pi-adic construction on X that you present better than this construction, but I still have very little intuition for these operators geometrically based upon the definition. I was hoping you could help me understand this.

Supposed X is a smooth manifold. Then any cohomology class in H^q(X) corresponds under Poincare duality to a linear combination of codim q submanifolds. For u\_Y a class in H^q(X) corresponding to a cidim q sub manifold Y, you can compute u\_Y \\cup u\_Y as the cohomology class of the self-intersection of this submanifold—e.g. as the cohomology class of the zero locus of a section of the N\_(Y/X) (or as the index q Stiefel-Whitney class of the normal bundle).

I've heard that Sq^i(u\_Y) corresponds to the index i Stiefel-Whitney class of Y. This gives me more intuition for these cohomology operations.

Is there a way to understand this in terms of the construction you gave?

Thanks!  
Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 7 Sep

Dear Isabel,

A more modern treatment of the cup-i approach is contained in the statement that the cochain functor (to DG algebras) lifts to a functor to E\_\\infty algebras. See Mandell, Cochain Multiplications, Am J Math 2002. This approach has its own virtues; for example, the cohomology of any co-commutative Hopf algebra comes equipped with Steenrod operations. (But they don't satisfy Sq^0=1; instead, they are induced by the Frobenius in the dual Hopf algebra.)

I think a reference for the construction you describe is McCrory, Cobordism operations and singularities of maps, BAMS 82 (1976) 281ff. I guess it's related to the statement, which I think we will hear from \[Student Name\], that SW classes correspond under the Thom isomorphism with Steenrod operations on the Thom class.

Haynes

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 9 Sep

_Response to:_ Serre, J. -P. "[Cohomologie Modulo 2 des Complexes d'Eilenberg-Maclane](http://dx.doi.org/10.1007/BF02564562)." _Commentari Mathematici Helvetici 27_, no. 1 (1953): 198–232.

Dear Prof. Miller,

Here is my response:

One of the things that stood out to me in this paper was how clean the computations of the cohomology ring mod 2 of K(Z/2, n) was. In particular, the fact that the Serre spectral sequence could determine this without computing any of the differentials (although this may be built into Borel's theorem, so maybe this isn't quite true).

A question this brings to mind is: does this technique generalize to mod p coefficients? This would be relevant to the P^i cohomology operations. From what I can tell, the only new input would need to be an analog of Borel's Theorem (which would come with some notion of a simple system of generators). Presumably this could classify operations of type (Z/p, Z/p, n, q) by Serre's notation. (And probably has been done...? I would be curious if it also used this spectral sequence technique.)

Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 11 Sep

Well, now ... it depends on what you mean by "compute." As \[Student Name\] pointed out, if you just started to compute H^\*(K\_2) from the spectral sequence, you'd have a tough time. You'd start by computing (if I may use that word) d\_2 i\_1 . Then somehow you would successively compute d\_3 i\_1^2, d\_5 i\_1^4, d\_9 i\_1^8, .... This is a pretty complicated spectral sequence, one which doesn't collapse at any finite stage. Once you've done the first computation, it's true that all the rest is built into Borel's theorem.

By the way, if you reorganize the differentials to be done all at once, what you have is a contractible complex of ... well, of comodules over H^\*(K\_1) as a coalgebra. You have a resolution of F\_2 as a comodule. The comodule primitives of the comodules in that resolution are given by the bottom row in the spectral sequence. This shows that H^\*(K\_2) is the derived functors of H^\*(K\_1)-comodule primitives applied to the comodule F\_2. Sanity check: the algebra dual to H^\*(K\_1) is exterior on classes in dimension 1, 2, 4, 8, .... Each gives a polynomial algebra in Ext, and the dimensions of the generators come out to be 2, 3, 5, 9, ....

Sure, the odd prime picture comes out just the same. The hardest thing is constructing the operations, which Hatcher describes very nicely. 'Simple system' means you can use powers up to the (p-1)st power of even generators.

Haynes

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 11 Sep

_Response to:_ Milnor, J. W. "[The Geometric Realization of a Semi–simplicial Complex](http://www.jstor.org/stable/1969967)." _Annals of Mathematics_ 65, no. 2 (1957): 357–62.

Dear Prof. Miller,

Here is my response:

Something that confused me when I was first reading the paper was the definition of the face and degeneracy maps of K and delta\_n, until I realized that on the level of the standard simplices, the face maps gave inclusion of an n-simplex as a face in an (n+1)-simplex and the degeneracy maps gave a projection from an n-simplex to some (n-1)-simplex (which is something of the opposite of what is happening with what I think of as the face and degeneracy maps of a simplicial set). Once I sorted this out, though, the notion of geometric realization he defines seems intuitive.

I guess I am wondering what is significant about this paper (or what is the key point to take away?) It seems that the notion of geometric realization was already defined, but I gather from the introduction that it doesn't give the desired nice properties when dealing with products. (Perhaps what's nice is the point that |K(pi, n)| is an abelian topological group? E.g. the space realizes the fact that something in the homotopy class of any K(pi, n) space will be a topological group.) I still feel the lack of motivation for this. Perhaps this will be filled in in \[Student Name's\] talk tomorrow.

Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 11 Sep

Dear Isabel,

This adjoint pair is a very general construction. If D is a small subcategory of C, then any X in C defines a functor D^{op} --> Sets by d |--> Hom\_C(d,X) . If C has colimits then this functor has a left adjoint, formed |K| = \\coprod\_d K(d) / an equivalence relation defined by the morphisms in d.

Part of what I wanted this paper to do was simply to introduce the idea of simplicial objects. But I think the main theorem is that |Sin(X)| --> X is a weak equivalence: it's a functorial resolution of X by a CW complex. If you define a map of simplicial sets to be a "weak equivalence" if it induces a weak (or equivalently homotopy) equivalence on realizations, then it follows that K --> Sin|X| is also a weak equivalence. This is saying that for homotopy theoretic purposes you can work in either category.

A main reason for using degeneracies is just what you say: they make products work correctly.

We'll see whether \[Student Name\] describes the Eilenberg model for K(pi,n). Here it is:

K(pi,n)\_\* = Z^n(\\Delta^\*,pi), n-cocycles on the standard simplicial simplex with coefficients in pi

\\Delta^n is the simplicial set \\DDelta(-,n) , where \\DDelta is the category with objects  
\[n\] = {0,1, ..., n}, n \\geq 0, and order preserving maps.

So the realization of this is a topological abelian group model for K(pi,n). (pi abelian of course)

Haynes

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 15 Sep

_Response to:_ Thom, R. "[Quelques propriétés globales des variétés différentiables](http://dx.doi.org/10.1007/BF02566923)." _Commentarii Mathematici Helvetici_ 28 (1954): 17–86.

Dear Professor Miller,

Here is my response:

First, could you give me a reference for the construction of the Thom class (and the Thom isomorphism...is this possible?) from the relative Serre spectral sequence for the fibration defined by the vector bundle? \[Student Name\] touched on this briefly in his practice talk and I was not very clear on what was happening. I also can't see quite how to get Thm 8.1 and the preceding cohomology groups on pg 89 from the Serre spectral sequence.

From what I can see we take the relative Serre spectral sequence converging to the cohomology H^n(D(E), S(E)), where D(E) is the total space of the disk bundle of the n-plane bundle and S(E) is the sphere bundle (which is, I think, the same as taking H^n(E, E\_0) where E\_0 is the nonzero elements): then the E\_2 page has 2 collections of points along the q=0 and q=n lines because the cohomology of the fibers is zero outside these degrees. It would seem, then, that the H^i(B) terms on the E\_2 page with p\<= n all survive to the infinity page (assuming they are nonzero), and it is only the higher terms that could be in the image of differentials. But this seems to contradict what is on pg 89. Also: how does a spectral sequence give you an identification of H^i(E, E\_0) with H^(i-n)(B)? It seems like (at least a quotient of) H^(n)(B) would be identified with a graded piece of H^n(E, E\_0)... I know that I must be doing something very silly... but I can't seem to figure out what it is... (e.g. the i-n index looks something like working in homology and then using Poincare duality?)

Thanks!  
Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 15 Sep

Thanks, Isabel.

In this case the relative Serre spectral sequence has the form

E\_2^{s,t} = H\_s(B;H\_t(F,F\_0)) ==> H^{s+t})(E,E\_0)

Well, H\_t(F,F\_0) is nonzero only for t=n, so there's at most one nonzero row. There might be local coefficients. A trivialization of this coefficient system is precisely an orientation of the vector bundle. Every bundle is uniquely oriented with mod 2 coefficients, so we find the only nonzero row is

E\_2^{s,n} = H\_s(B)

The spectral sequence collapses; there is only one nonzero associated quotient group in each dimension; and so there is a canonical isomorphism

H\_{s+n}(E,E\_0) = H\_s(B)

Under it, u corresponds to 1. Restricting to a fiber shows that this u restricts to the generator. The multiplicative structure of the spectral sequence guarantees that the isomorphism is given by cupping with u.

I wrote this before reading your second paragraph; does it answer your question?

The Serre spectral sequence leads to an easy proof of the splitting principle too: It's enough to split off a single line bundle. The universal way to do that is to pull back to the projective bundle, so we want to see that the projection map from the projective bundle is monic. Look at the Serre spectral sequence; the fiber is RP^{n-1}; again no issue of orientability mod 2; by the multiplicative structure we just have to see that the generator a in E\_2^{0,1} survives; and an explicit geometric construction shows that it does. What's that construction?

Haynes

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 17 Sep

_Response to:_ Milnor, J. W., and J. D. Stasheff. Characteristic Classes (_Annals of Mathematical Studies_). Vol. 76. Princeton University Press, 1974. ISBN: 9780691081229. \[Preview with [Google Books](http://books.google.com/books?id=5zQ9AFk1i4EC&pg=PAfrontcover)\]

Dear Professor Miller,

Here is my response:

The main theorem of Chapter 2 is really how I want to understand (co)homology of smooth manifolds -- in terms of fundamental classes of submanifolds. (This of course related to my intuition about the Chow ring of an algebraic variety). If I understand this main theorem correctly, then this is well-founded if I am considering (lets do mod 2 coefficients) a submanifold of dimension \< half the dimension of the manifold. So transferring this to cohomology, we have that that cohomology classes of degree > half the dimension of the manifold correspond (via poincare duality and the above) to submanifolds of codim = deg (=> dimension = n-deg which by assumption is \< n/2).

Question: are there conditions upon the manifold under which this is true of all dimensions (up to taking linear combinations, such as in the integral coefficient case)?

(Is this obvious from the condition of the manifold being orientable in the Z case)?

e.g. Is the converse true under general condition?

My other question is, where does the obstruction to this being true in general come from in the problem? My first thought would be that you have a nontrivial normal bundle, but in the case that G reduces to a point, Theorem II.4 on pg 146 seems still to suggest this condition on the dimension... (silly question: how did the "and" in Thm II.3 turn into an "or" in Thm II.4?)

I am also a little confused about the appearance of the Stiefel-Whitney classes in the cohomology of Grassmannians but maybe this will be cleared up by the talk today.

Thank you in advance!  
Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 18 Sep

Great questions. Thom answers them in the way topologists answer such questions: he reduces them to calculations.

Take the unoriented case for example. So a in H\_k(V^n;Z/2) is representable by a manifold iff its Poincare dual x is "representable." This means that the map x : V --> K(Z/2,n-k) lifts to a map V --> MO(n-k). If n \< 2(n-k) we are in the stable range; MO(n-k) is a product of Eilenberg Mac Lane spaces; the Thom class u : MO(n-k) --> K(Z/2,n-k) splits, so there is a lift and there is a submanifold. But if n > 2(n-k) (or maybe equal) then more complicated parts of the homotopy type of MO(n-k) get involved. One thing to check first is whether such a lift is compatible with Steenrod operations. It becomes a calculation. We could try to work out some examples. The oriented case is similar, and in fact the almost-complex case is similar too, maybe more relevant to complex manifolds.

The cohomology of real Grassmannians is made up of SW classes.... did this get clarified?

Haynes

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 22 Sep

_Response to:_ Milnor, J. W., and J. D. Stasheff. Characteristic Classes (_Annals of Mathematical Studies_). Vol. 76. Princeton University Press, 1974. ISBN: 9780691081229. \[Preview with [Google Books](http://books.google.com/books?id=5zQ9AFk1i4EC&pg=PAfrontcover)\]

Dear Prof. Miller,

Here is my second response on this paper:

Since I already responded to the sections of the paper that will be covered on Monday, I will build on my response from last week.

1.  I worked out clearly how he gets that the classifying space for O(k) is G\_k, the Grassmannian of k-planes in R^m for m sufficiently large (let's just say R^\\infty). This comes from the fact that E\_O(k) is the Steifel manifold V\_k(R^\\infty) of k-frames in R^\\inft—clearly the O(k) action permutes these k orthogonal vectors transitively and the kernel of this action is hence G\_k. So it suffices to show that V\_k(R^\\infty) is contractible. But this follows from induction on k... when k is 0 it is obvious. Then we use the fact that we have a fibration V\_{k-1}(R^\\infty) \\to V\_k(R^\\infty) \\to S^\\infty, for which the last map is taking the last/first element of the k-frame. The space V\_{k-1}(R^\\infty) is contractible by assumption... but so is S^\\infty, so using the LES in homotopy associated to this fibration we get the desired result.
2.  I've cleared up my understanding of the cohomology of Grassmannians in terms of Steifel-Whitney classes. I see that these SW classes are associated to the obvious k-plane bundle on G\_k, and I looked at an example of relating this to Schubert cells in the case of k=2, m=4. This cleared things up for me substantially.
3.  I'd like to understand better what happens outside of the stable region for n > 2(n-k) and what the Steenrod operations might tell you (maybe we could talk about this). I'd like to get some intuition for what goes wrong when this realization question isn't true.

Thanks!  
Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 22 Sep

1.  Yes, terrific. This also shows why G\_{k-1} is the sphere bundle of E\_k --> G\_k , more directly than what \[Student Name\] did today: the sphere bundle is V\_k x\_O(k) S^{k-1}, but S^{k-1} = O(k)/O(k-1), so V\_k x\_O(k) S^{k-1} = V\_k/O(k-1) . The O(k-1) action is free (since the O(k) action was), and V\_k is still contractible, so this is just another model for G\_{k-1} .
2.  The Schubert cell picture is beautiful. The actual ring structure of Gr\_k(R^n) (or the complex version) is very complicated, though the Poincare series isn't so bad. Actually you can generalize this computation in two ways: you can compute the cohomology of the flag manifold of decompositions of R^k into subspaces of dimensions k\_1, .... k\_n ; and you can do this on each fiber of a vector bundle and describe the cohomology of the flag bundle.
3.  I tried to think through a little of this in my last response. Do you agree that any 2-dimensional cohomology class in an oriented compact manifold is Poincare dual to a submanifold? But we should be able to come up with counter examples in higher dimension, even without assuming orientability. There are more detailed questions, such as: what is the minimal genus of a surface representing a given class in a 4-manifold. This is very hard and geometric ....

Haynes

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 26 Sep

_Response to:_ Milnor, J. W., and J. D. Stasheff. "Signature Theorem." In Characteristic Classes (Annals of Mathematical Studies). Vol. 76. Princeton University Press, 1974. ISBN: 9780691081229. \[Preview with [Google Books](http://books.google.com/books?id=5zQ9AFk1i4EC&pg=PA219=onepage)\]

Dear Professor Miller,

Here is my response for the signature theorem reading:

The first thing I thought of while reading this was this "What is..." article someone who does differential geometry sent (attached) me when I told them I was writing my thesis on formal group laws \[not that I still really understand the connection\]. It gives a really nice introduction to multiplicative genera and how Hirzebruch's theorem fits in. I like the motivation that this article as well as the reading from Milnor&Stasheff gives that such genera (well, the reading only says the signature) are depend only upon the cobordism class of the manifold, and that all homomorphisms from \\Omega\_\* to Q are Q-linear combinations of Pontrjagin numbers (and hence can be given by the "multiplicative sequences" K that Hirzebruch defines), and so it makes sense that we should be able to find such a sequence for the signature.

I can see that this "multiplicative sequence" L that Hirzebruch defines for the signature is very related to the "logarithm" of the signature that is defines in that AMS article (well, clearly, since one is \\sqrt(t)tanh^{-1}(\\sqrt{t}) and the other is tanh^{-1}(t)), but I need to wrap my head around this a little more to see how exactly (I am certain that after class today I'll have a clear enough picture to see this, its just unwrapping definitions.)

From the other chapters of reading, I would really like to understand the proof of Cor 18.9 that over Q the oriented cobordism ring is generated by the classes of the P^{2k}(C), but this was spread over many chapters and I didn't spend long enough to completely trace through the argument in detail. I understand that the key steps are (1) showing that the 4nth degree of the cobordism ring is of dimension p(n), and (2) showing that the classes of P(C)^{2i\_1} x... x P(C)^{2i\_r} are independent as i\_k range over all partitions of n. This last point comes from looking at characteristic classes, but I need to spend more time on this to understand it completely.

Thanks!  
Isabel

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 26 Sep

Dear Isabel,

I'd forgotten \[…\] article. Earlier Graeme Segal wrote a Bourbaki Seminar note on elliptic cohomology with a similar summary of this story. I was urging \[Student Name\] to make the relationships a little clearer, but his focus was different. I could have referred to Hirzebruch's book for this story, too.

As you know, there's another perspective on (weakly almost) complex genera, which lets you think about ring homomorphisms into rings which are not Q-algebras: a homomorphism MU\_\* --> R is the same thing as a formal group law over R. It's logarithm is the 'logarithm of the genus.' The genus factors through MSO\_\* iff the corresponding formal group law enjoys a certain symmetry, which causes the odd coefficients in the logarithm to vanish. The hyperbolic tangent occurs by symmetrizing the exponential ....

If you are willing to use the fact that MU\_\* is the Lazard ring, then you know that its rationalization is generated by the coefficients of the logarithm, because over a Q-algebra any formal group is isomorphic to the additive formal group. So knowing "Miscenko's theorem" (the formula Ochanine gives for the logarithm) tells you that the CP^n's generate MU\_\* rationally. The MSO case is the "even" part of that statement.

But yes, this story is worth spending more time on!

Haynes