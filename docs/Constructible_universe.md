---
title: Constructible universe
permalink: Constructible_universe
redirect_from:
  - L
  - Silver_cardinal
  - Zero_dagger
  - Zero_sharp
---

The Constructible universe (denoted $L$) was invented by Kurt Gödel as a
transitive inner model of
[$\\text{ZFC+}$](ZFC "ZFC")<a href="/web/20191022214445/http://cantorsattic.info/GCH" class="mw-redirect" title="GCH">$\text{GCH}$</a>
(assuming the consistency of $\\text{ZFC}$) showing that $\\text{ZFC}$
cannot disprove $\\text{GCH}$. It was then shown to be an important
model of $\\text{ZFC}$ for its satisfying of other axioms, thus making
them consistent with $\\text{ZFC}$. The idea is that $L$ is built up by
ranks like $V$. $L\_0$ is the empty set, and $L\_{\\alpha+1}$ is the set
of all easily definable subsets of $L\_\\alpha$. The assumption that
$V=L$ (also known as the **Axiom of constructibility**) is undecidable
from $\\text{ZFC}$, and implies many axioms which are consistent with
$\\text{ZFC}$. A set $X$ is **constructible** iff $X\\in L$. $V=L$ iff
every set is constructible.


## Definition

$\\mathrm{def}(X)$ is the set of all "easily definable" subsets of $X$
(specifically the $\\Delta\_0$ definable subsets). More specifically, a
subset $x$ of $X$ is in $\\mathrm{def}(X)$ iff there is a first-order
formula $\\varphi$ and $v\_0,v\_1...v\_n\\in X$ such that $x=\\{y\\in
X:\\varphi^X\[y,v\_0,v\_1...v\_n\]\\}$. Then, $L\_\\alpha$ and $L$ are
defined as follows:

-   $L\_0=\\emptyset$
-   $L\_{\\alpha+1}=\\mathrm{def}(L\_\\alpha)$
-   $L\_\\beta=\\bigcup\_{\\alpha&lt;\\beta} L\_\\alpha$ if $\\beta$ is
    a limit ordinal
-   $L=\\bigcup\_{\\alpha\\in\\mathrm{Ord}} L\_\\alpha$

### The Relativized constructible universes $L\_\\alpha(W)$ and $L\_\\alpha\[W\]$

$L\_\\alpha(W)$ for a class $W$ is defined the same way except
$L\_0(W)=\\text{TC}(\\{W\\})$ (the transitive closure of $\\{W\\}$).
$L\_\\alpha\[W\]$ for a class $W$ is defined in the same way as $L$
except using $\\mathrm{def}\_W(X)$, where $\\mathrm{def}\_W(X)$ is the
set of all $x\\subseteq X$ such that there is a first-order formula
$\\varphi$ and $v\_0,v\_1...v\_n\\in X$ such that $x=\\{y\\in
X:\\varphi^X\[y,W,v\_0,v\_1...v\_n\]\\}$ (because the relativization of
$\\varphi$ to $X$ is used and $\\langle X,\\in\\rangle$ is not used,
this definition makes sense even when $W$ is not in $X$).

$L\[W\]=\\bigcup\_{\\alpha\\in\\mathrm{Ord}}L\_\\alpha\[W\]$ is always a
model of $\\text{ZFC}$, and always satisfies $\\text{GCH}$ past a
certain cardinality.
$L(W)=\\bigcup\_{\\alpha\\in\\mathrm{Ord}}L\_\\alpha(W)$ is always a
model of $\\text{ZF}$ but need not satisfy $\\text{AC}$ (the axiom of
choice). In particular, $L(\\mathbb{R})$ is, under large cardinal
assumptions, a model of the [axiom of
determinacy](Axiom_of_determinacy "Axiom of determinacy").
However, Shelah proved that if $\\lambda$ is a strong limit cardinal of
uncountable cofinality then $L(\\mathcal{P}(\\lambda))$ is a model of
$\\text{AC}$.

## The difference between $L\_\\alpha$ and $V\_\\alpha$

For $\\alpha\\leq\\omega$, $L\_\\alpha=V\_\\alpha$. However,
$\|L\_{\\omega+\\alpha}\|=\\aleph\_0 + \|\\alpha\|$ whilst
$\|V\_{\\omega+\\alpha}\|=\\beth\_\\alpha$. Unless $\\alpha$ is a
[$\\beth$-fixed
point](Beth "Beth"),
$\|L\_{\\omega+\\alpha}\|&lt;\|V\_{\\omega+\\alpha}\|$. Although
$L\_\\alpha$ is quite small compared to $V\_\\alpha$, $L$ is a tall
model, meaning $L$ contains every ordinal. In fact,
$V\_\\alpha\\cap\\mathrm{Ord}=L\_\\alpha\\cap\\mathrm{Ord}=\\alpha$, so
the ordinals in $V\_\\alpha$ are precisely those in $L\_\\alpha$.

If $0^{\\\#}$ exists (see below), then every uncountable cardinal
$\\kappa$ has $L\\models$"$\\kappa$is [totally
ineffable](Ineffable "Ineffable")
(and therefore the smallest actually totally ineffable cardinal
$\\lambda$ has many more large cardinal properties in $L$).

However, if $\\kappa$ is
[inaccessible](Inaccessible "Inaccessible")
and $V=L$, then $V\_\\kappa=L\_\\kappa$. Furthermore,
$V\_\\kappa\\models (V=L)$. In the case where $V\\neq L$, it is still
true that $V\_\\kappa^L=L\_\\kappa$, although $V\_\\kappa^L$ will not be
$V\_\\kappa$. In fact, $\\mathcal{P}(\\omega)\\not\\in V\_\\kappa^L$ if
$0^{\\\#}$ exists.

## Statements True in $L$

Here is a list of statements true in $L$ of any model of $\\text{ZF}$:

-   $\\text{ZFC}$ (and therefore the Axiom of Choice)
-   $\\text{GCH}$
-   $V=L$ (and therefore $V$ $=$
    [$\\text{HOD}$](HOD "HOD"))
-   The [diamond
    principle](Diamond_principle "Diamond principle")
-   The
    <a href="index.php?title=Clubsuit_principle&amp;action=edit&amp;redlink=1" class="new" title="Clubsuit principle (page does not exist)">clubsuit principle</a>
-   The falsity of
    <a href="index.php?title=Suslin%27s_hypothesis&amp;action=edit&amp;redlink=1" class="new" title="Suslin&#39;s hypothesis (page does not exist)">Suslin's hypothesis</a>

## Determinacy of $L(\\R)$

*Main article: [axiom of
determinacy](Axiom_of_determinacy#Determinacy_of_.24L.28.5Cmathbb.7BR.7D.29.24 "Axiom of determinacy")*

## Using other logic systems than first-order logic

When using second order logic in the definition of $\\mathrm{def}$, the
new hierarchy is called $L\_\\alpha^{II}$. Interestingly,
$L^{II}=\\text{HOD}$. When using $\\mathcal{L}\_{\\kappa,\\kappa}$, the
hierarchy is called $L\_\\alpha^{\\mathcal{L}\_{\\kappa,\\kappa}}$, and
$L\\subseteq L^{\\mathcal{L}\_{\\kappa,\\kappa}}\\subseteq
L(V\_\\kappa)$. Finally, when using $\\mathcal{L}\_{\\infty,\\infty}$,
it turns out that the result is $V$.

Chang's Model is $L^{\\mathcal{L}\_{\\omega\_1,\\omega\_1}}$. Chang
proved that $L^{\\mathcal{L}\_{\\kappa,\\kappa}}$ is the smallest inner
model of $\\text{ZFC}$ closed under sequences of length $&lt;\\kappa$.

## Silver indiscernibles

*To be expanded.*

## Silver cardinals

A cardinal $κ$ is **Silver** if in a set-forcing extension there is a
club in $κ$ of generating indiscernibles for $V\_κ$ of order-type $κ$.
This is a very strong property downwards absolute to $L$,
e.g.:{% cite Gitmana %}

-   Every element of a club $C$ witnessing that $κ$ is a Silver cardinal
    is
    <a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">virtually rank-into-rank</a>.
-   If $C ∈ V\[H\]$, a forcing extension by $\\mathrm{Coll}(ω, V\_κ)$,
    is a club in $κ$ of generating indiscernibles for $V\_κ$ of
    order-type $κ$, then each $ξ ∈ C$ is $&lt;
    ω\_1$-<a href="Iterable" class="mw-redirect" title="Iterable">iterable</a>.

## Sharps

$0^{\\\#}$ (zero sharp) is a
[$\\Sigma\_3^1$](Projective "Projective")
real number which, under the existence of many Silver indiscernibles (a
statement independent of $\\text{ZFC}$), has a certain number of
properties that contredicts the
<a href="L" class="mw-redirect" title="L">axiom of constructibility</a>
and implies that, in short, $L$ and $V$ are "*very different*".
Technically, under the standard definition of $0^\\\#$ as a (real number
encoding a) set of formulas, $0^\\\#$ provably exists in $\\text{ZFC}$,
but lacks all its important properties. Thus the expression "$0^\\\#$
exists" is to be understood as "$0^\\\#$ exists *and* there are
uncountably many Silver indiscernibles".

### Definition of $0^{\\\#}$

Assume there is an uncountable set of Silver indiscernibles. Then
$0^{\\\#}$ is defined as the set of all Gödel numberings of first-order
formula $\\varphi$ such that
$L\_{\\aleph\_{\\omega}}\\models\\varphi(\\aleph\_0,\\aleph\_1...\\aleph\_n)$
for some $n$.

"$0^{\\\#}$ exists" is used as a shorthand for "there is an uncountable
set of Silver indiscernibles"; since $L\_{\\aleph\_\\omega}$ is a set,
$\\text{ZFC}$ can define a truth predicate for it, and so the existence
of $0^{\\\#}$ as a mere set of formulas would be trivial. It is
interesting only when there are many (in fact proper class many) Silver
indiscernibles. Similarly, we say that "$0^{\\\#}$ does not exist" if
there are no Silver indiscernibles.

### Implications, equivalences, and consequences of $0^♯$'s existence

If $0^♯$ exists then:

-   $L\_{\\aleph\_\\omega}\\prec L$ and so $0^♯$ also corresponds to the
    set of the Gödel numberings of first-order formulas $\\varphi$ such
    that $L\\models\\varphi(\\aleph\_0,\\aleph\_1...\\aleph\_n)$
-   In fact, $L\_\\kappa\\prec L$ for every Silver indiscernible, and
    thus for every uncountable cardinal.
-   Given any set $X\\in L$ which is first-order definable in $L$,
    $X\\in L\_{\\omega\_1}$. This of course implies that $\\aleph\_1$ is
    not first-order definable in $L$, because $\\aleph\_1\\not\\in
    L\_{\\omega\_1}$. This is already a disproof of $V=L$ (because
    $\\aleph\_1$ is first-order definable).
-   For every $\\alpha\\in\\omega\_1^L$, every Silver indiscernible (and
    in particular every uncountable cardinal) in $L$ is a Silver
    cardinal,
    [$\\alpha$-iterable](Ramsey#iterable "Ramsey"),
    $\\geq$ an
    [$\\alpha$-Erdős](Erdos "Erdos"),
    [totally
    ineffable](Ineffable "Ineffable")
    and
    <a href="Completely_remarkable" class="mw-redirect" title="Completely remarkable">completely remarkable</a>
    and has most other virtual large cardinal properties and other large
    cardinal properties consistent with
    $V=L$.{% cite Gitmana Bagaria2017a %}
-   There are only countably many reals in $L$, i.e. $\|\\R\\cap
    L\|=\\aleph\_0$ in $V$.
-   By [elementary-embedding absoluteness
    results](Elementary_embedding#Absoluteness "Elementary embedding")
    (The hypothesis can be weakened, because one can chop at off the
    universe at any Silver indiscernible and use
    reflection.):{% cite Gitman2018 %}
    -   $L$, equipped with only its definable classes, is a model of the
        <a href="Generic_Vop%C4%9Bnka%27s_Principle" class="mw-redirect" title="Generic Vopěnka&#39;s Principle">generic Vopěnka principle</a>.
    -   In $L$ there are numerous [virtual
        rank-into-rank](Rank_into_rank#Virtually_rank-into-rank "Rank into rank")
        embeddings $j : V\_θ^L → V\_θ^L$, where $θ$ is far above the
        supremum of the critical sequence.
    -   Therefore every Silver indiscernible
        -   is [virtually
            $A$-extendible](Extendible#Virtually_extendible_cardinals "Extendible")
            in $L$ for every definable class $A$
        -   and is the critical point of virtual rank-into-rank
            embeddings with targets as high as desired and fixed points
            as high above the critical sequence as desired.
-   There is a class-forcing notion $\\mathbb{P}$ definable in $L$, such
    that in any $L$-generic extension $L\[C\]$ by this forcing,
    $\\text{GBC}$ and the generic Vopěnka principle hold, yet
    [$\\text{Ord}$ is not
    Mahlo](ORD_is_Mahlo "ORD is Mahlo").{% cite Gitman2018 %}
    -   Proof includes a lemma stating: For any ordinal $δ$ and any
        natural number (of the meta-theory — this lemma is a scheme)
        $n$, if $D\_{δ,n} ⊂ \\mathbb{P}$ is the collection of conditions
        $c$ for which there is an ordinal $θ$ such that
        -   $L\_θ ≺\_{Σ\_n} L$,
        -   $c ∩ θ$ is $L\_θ$-generic for $\\mathbb{P}^{L\_θ}$ and
        -   in some forcing extension of $L$, there is an elementary
            embedding
            $j : ⟨ L\_θ , ∈, c ∩ θ ⟩ → ⟨ L\_θ , ∈, c ∩ θ ⟩$
            with critical point above $δ$,

        then $D\_{δ,n}$ is a definable dense subclass of $\\mathbb{P}$
        in $L$.
-   There is a definable class-forcing notion in $L$, such that in the
    corresponding $L$-generic extension, $\\text{GBC}$ holds, the
    generic Vopěnka scheme holds, but $\\text{Ord}$ is not definably
    Mahlo, because there is a $∆\_2$-definable club class avoiding the
    regular cardinals.
-   There is a class-forcing extension $L\[G\]$ of the constructible
    universe in which the generic Vopěnka principle holds (so $gVP(κ,
    \\mathbf{Σ\_{n+1}})$ and $gVP(Π\_n)$ hold for any $κ$ and $n$), but
    there are no $Σ\_2$-reflecting cardinals and hence no remarkable
    cardinals (or $n$-remarkable
    cardinals).{% cite Gitman2018 %}

The following statements are equivalent:

-   There is an uncountable set of Silver indiscernibles (i.e. "$0^♯$
    exists")
-   There is a proper class of Silver indiscernibles (unboundedly many
    of them).
-   There is a unique well-founded remarkable E.M. set (see below).
-   Jensen's Covering Theorem fails (see below).
-   $L$ is thin, i.e. $\|L\\cap V\_\\alpha\|=\|\\alpha\|$ for all
    $\\alpha\\geq\\omega$.
-   $\\Sigma^1\_1$-<a href="Axiom_of_projective_determinacy" class="mw-redirect" title="Axiom of projective determinacy">determinacy</a>
    (lightface form).
-   $\\aleph\_\\omega$ is regular (hence weakly inaccessible) in $L$.
-   There is a nontrivial [elementary
    embedding](Elementary_embedding "Elementary embedding")
    $j:L\\to L$.
-   There is a proper class of nontrivial elementary embeddings $j:L\\to
    L$.
-   There is a nontrivial elementary embedding $j:L\_\\alpha\\to
    L\_\\beta$ with $\\text{crit}(j)&lt;\|\\alpha\|$.

The existence of $0^♯$ is implied by:

-   [Chang's
    conjecture](Chang%27s_conjecture "Chang's conjecture")
-   Both $\\omega\_1$ and $\\omega\_2$ being singular (requires
    $\\neg\\text{AC}$).
-   The negation of the singular cardinal hypothesis ($\\text{SCH}$).
-   The existence of an $\\omega\_1$-iterable cardinal or of a
    $\\omega\_1$-Erdős cardinal.
-   The existence of a weakly compact cardinal $\\kappa$ such that
    $\|(\\kappa^+)^L\|=\\kappa$.
-   The existence of some uncountable regular cardinal $\\kappa$ such
    that every constructible $X\\subseteq\\kappa$ either contains or is
    disjoint from a closed unbounded set.

Note that if $0^♯$ exists then for every Silver indiscernible (in
particular for every uncountable cardinal) there is a nontrivial
[elementary
embedding](Elementary_embedding "Elementary embedding")
$j:L\\rightarrow L$ with that indiscernible as its critical point. Thus
if any such embedding exists, then a proper class of those embeddings
exists.

### Nonexistence of $0^\\\#$, Jensen's Covering Theorem

### EM blueprints and alternative characterizations of $0^\\\#$

An **EM blueprint** (Ehrenfeucht-Mostowski blueprint) $T$ is any theory
of the form
$\\{\\varphi:(L\_\\delta;\\in,\\alpha\_0,\\alpha\_1...)\\models\\varphi\\}$
for some ordinal $\\delta&gt;\\omega$ and
$\\alpha\_0&lt;\\alpha\_1&lt;\\alpha\_2...$ are indiscernible in the
structure $L\_\\delta$. Roughly speaking, it's the set of all true
statements about $\\alpha\_0,\\alpha\_1,\\alpha\_2...$ in $L\_\\delta$.

For an EM blueprint
$T=\\{\\varphi:(L\_\\delta;\\in,\\alpha\_0,\\alpha\_1...)\\models\\varphi\\}$,
**the theory $T^{-}$** is defined as
$\\{\\varphi:L\_\\delta\\models\\varphi\\}$ (the set of truths about any
definable elements of $L\_\\delta$). Then, **the structure
$\\mathcal{M}(T,\\alpha)=(M(T,\\alpha);E)\\models T^{-}$** has a very
technical definition, but it is indeed uniquely (up to isomorphism) the
only structure which satisfies the existence of a set $X$ of
$\\mathcal{M}(T,\\alpha)$-ordinals such that:

1.  $X$ is a set of indiscernibles for $\\mathcal{M}(T,\\alpha)$ and
    $(X;E)\\cong\\alpha$ ($X$ has order-type $\\alpha$ with respect to
    $\\mathcal{M}(T,\\alpha)$)
2.  For any formula $\\varphi$ and any $x&lt;y&lt;z...$ with
    $x,y,z...\\in X$,
    $\\mathcal{M}(T,\\alpha)\\models\\varphi(x,y,z...)$ iff
    $\\mathcal{M}(T,\\alpha)\\models\\varphi(\\alpha\_0,\\alpha\_1,\\alpha\_2...)$
    where $\\alpha\_0,\\alpha\_1...$ are the indiscernibles used in the
    EM blueprint.
3.  If $&lt;$ is an $\\mathcal{M}(T,\\alpha)$-definable
    $\\mathcal{M}(T,\\alpha)$-well-ordering of
    $\\mathcal{M}(T,\\alpha)$, then:
    $$\\mathcal{M}(T,\\alpha)=\\{\\min{}\_&lt;^{\\mathcal{M}(T,\\alpha)}\\{x:\\mathcal{M}(T,\\alpha)\\models\\varphi\[x,a,b,c...\]\\}:\\varphi\\in\\mathcal{L}\_\\in\\text{
    and } a,b,c...\\in X\\}$$

$0^\\\#$ is then defined as the **unique** EM blueprint $T$ such that:

1.  $\\mathcal{M}(T,\\alpha)$ is isomorphic to a transitive model
    $M(T,\\alpha)$ of ZFC for every $\\alpha$
2.  For any infinite $\\alpha$, the set of indiscernibles $X$ associated
    with $M(T,\\alpha)$ can be made cofinal in
    $\\text{Ord}^{M(T,\\alpha)}$.
3.  The $L\_\\delta$-indiscernables $\\beta\_0&lt;\\beta\_1...$ can be
    made so that if $&lt;$ is an $M(T,\\alpha)$-definable well-ordering
    of $M(T,\\alpha)$, then for any $(m+n+2)$-ary formula $\\varphi$
    such that
    $\\min\_&lt;^{M(T,\\alpha)}\\{x:\\varphi\[x,\\beta\_0,\\beta\_1...\\beta\_{m+n}\]\\}&lt;\\beta\_m$,
    then:
    $$\\min{}\_&lt;^{M(T,\\alpha)}\\{x:\\varphi\[x,\\beta\_0,\\beta\_1...\\beta\_{m+n}\]\\}=\\min{}\_&lt;^{M(T,\\alpha)}\\{x:\\varphi\[x,\\beta\_0,\\beta\_1...\\beta\_{m-1},\\beta\_{m+n+1}...\\beta\_{m+2n+1}\]\\}$$

If the EM blueprint meets 1. then it is called *well-founded.* If it
meets 2. and 3. then it is called *remarkable.*

If $0^\\\#$ exists (i.e. there is a well-founded remarkable EM
blueprint) then it happens to be equivalent to the set of all $\\varphi$
such that $L\\models\\varphi\[\\kappa\_0,\\kappa\_1...\]$ for some
uncountable cardinals $\\kappa\_0,\\kappa\_1...&lt;\\aleph\_\\omega$.
This is because the associated $M(T,\\alpha)$ will always have
$M(T,\\alpha)\\prec L$ and furthermore $\\kappa\_0,\\kappa\_1...$ would
be indiscernibles for $L$.

$0^\\\#$ exists interestingly iff some $L\_\\delta$ has an uncountable
set of indiscernables. If $0^\\\#$ exists, then there is some
uncountable $\\delta$ such that $M(0^\\\#,\\omega\_1)=L\_\\delta$ and
$L\_\\delta$ therefore has an uncountable set of indiscernables. On the
other hand, if some $L\_\\delta$ has an uncountable set of
indiscernables, then the EM blueprint of $L\_\\delta$ is $0^\\\#$.

### Sharps of arbitrary sets

### Generalisations

$0^\\dagger$ (zero dagger) is a set of integers analogous to $0^\\sharp$
and connected with inner models of
[measurability](Measurable "Measurable").{% cite Kanamori1990 %}

$0^{sword}$ is connected with nontrivial [Mitchell
rank](Mitchell_rank "Mitchell rank").
$¬ 0 ^{sword}$ (*not zero sword*) means that there is no
<a href="Mouse" class="mw-redirect" title="Mouse">mouse</a>
with a measure of Mitchell order $&gt;
0$.{% cite Sharpe2011 %}

$0^\\P$ (zero pistol) is connected with
[strong](Strong "Strong")
cardinals. $¬ 0^\\P$ (*not zero pistol*) means that a [core
model](Core_model "Core model")
may be built with a strong cardinal, but that there is no class of
indiscernibles for it that is closed and unbounded in
$\\mathrm{Ord}$).{% cite Sharpe2011 %}
$0^¶$ is “the sharp for a strong cardinal”, meaning the minimal sound
active mouse $\\mathcal{M}$ with $M \| \\mathrm{crit}(\\dot
F^{\\mathcal{M}}) \\models \\text{“There exists a strong cardinaly”}$,
with $\\dot F^{\\mathcal{M}}$ being the top extender of
$\\mathcal{M}$.{% cite Nielsen2018 %}

## Additional References

-   {% cite Jech2003 %}
-   user46667, *Gödel's Constructible Universe in Infinitary Logics (A
    Possible Approach to HOD Problem)*, URL (version: 2014-03-17):
    <a href="https://mathoverflow.net/q/156940" class="external free">https://mathoverflow.net/q/156940</a>
-   {% cite Chang1971 %}

