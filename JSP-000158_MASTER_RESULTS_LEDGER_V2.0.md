Erdős Problem #160 — Research Progress and Mathematical Results

Project: JSP-000158
Researcher: Hongzhao Zhang (张洪诏)
Research Team: DAZHuzhang. Art Team
Status: OPEN — Ongoing Research
Research Update: November 28, 2026
License: CC BY 4.0 (subject to the repository’s license file)

⸻

1. Overview

This repository documents an ongoing independent research project on Erdős Problem #160.

The central problem concerns colorings of the integers in which every nontrivial four-term arithmetic progression contains at least three distinct colors.

The research investigates the relationship between arithmetic-progression-free sets, multi-color configurations, finite combinatorial structures, and asymptotic bounds on the minimum number of colors required.

Over the course of the project, several complementary mathematical approaches have been developed, including:

* Pair-Union extremal theory.
* Three-set joint rigidity.
* Local arithmetic-progression extension structures.
* Combinatorial energy identities.
* Finite hypergraph certificates.
* Zero-density and finite-model transformations.
* Historical model reconstruction and source verification.

The project has produced a growing collection of mathematical identities, structural lemmas, finite certificates, and independently audited arguments.

Important: Erdős Problem #160 remains OPEN in this project. The results documented here should not be interpreted as a complete solution of the original problem.

2. Mathematical Framework

Let $h(N)$ denote the minimum number of colors needed to color $[1,N]$ such that every nontrivial four-term arithmetic progression

$$
a,
a+d,
a+2d,
a+3d,\qquad d\geq 1
$$

contains at least three distinct colors.

The research focuses on understanding the extremal structure imposed by this condition.

A particularly important approach is to translate coloring constraints into conditions on unions of disjoint sets.

This provides a connection between coloring problems and extremal arithmetic-progression-free set theory.

3. Major Research Results

3.1 Finite Combinatorial Models

The project has investigated several finite instances and associated coloring configurations.

The recorded results include:

* A four-coloring witness for $N=12$.
* A finite lower-bound result for $N=13$.
* The established finite range $13\leq N\leq22$, where $h(N)=4$.
* A recorded count of 144 four-color configurations at $N=22$.
* The nonexistence of a four-coloring at $N=23$, yielding $h(N)\geq5$ for $N\geq23$.

The finite SAT encoding for $N=13$ was recorded as:

$$
\texttt{p cnf 39 184}.
$$

The associated arithmetic-progression mapping audit passed all 132 checks.

These finite results are kept separate from asymptotic claims.

3.2 Pair-Union Theory

One of the central developments is a reformulation of the coloring problem using three pairwise-disjoint sets:

$$
C_1,C_2,C_3\subseteq[M].
$$

The principal constraint is that every pairwise union

$$
C_1\cup C_2,\quad C_1\cup C_3,\quad C_2\cup C_3
$$

is four-term-arithmetic-progression-free.

This formulation allows the original coloring condition to be studied through extremal set theory.

Let $r_4(M)$ denote the maximum size of a four-term-arithmetic-progression-free subset of $[M]$.

Define

$$
d_{ij}=r_4(M)-|C_i\cup C_j|
$$

and

$$
S=|C_1|+|C_2|+|C_3|.
$$

The project establishes the identity

$$
\boxed{d_{12}+d_{13}+d_{23}=3r_4(M)-2S.}
$$

This identity provides a basic quantitative framework for studying the simultaneous extremal behavior of the three pairwise unions.

The distinction between $F_3(M)$, which permits empty classes, and $F_3^+(M)$, which requires all three classes to be nonempty, is also retained throughout the analysis.

Research status: The foundational reformulation and deficit identity are proved.

3.3 Local Structural and Energy Methods

The Pair-Union investigation has developed a sequence of local structural constraints and energy identities.

Among the recorded results are:

* Restrictions on the lengths of consecutive missing-label runs.
* Constraints on adjacent labels around length-two runs.
* Inheritance of local restrictions by arithmetic subsequences.
* Difference identities and energy relations.
* Geometric energy upper bounds.
* Local window estimates.
* Variance upper bounds.

In particular, the project establishes the local estimate

$$
E_D(X;J_i)\leq\frac23 k_iD
$$

within its specified model.

The corresponding combination with earlier identities yields a variance upper bound.

However, these results do not yet establish the global joint-energy inequality required for the intended extremal improvement.

The distinction between local energy control and global joint rigidity remains essential.

3.4 ABBA Structure and Orthogonality

Another research direction investigates ABBA configurations and their associated arithmetic-progression constraints.

The documented mathematical progress includes:

* Common-relation identities.
* Corrected distance-indexed orthogonality.
* Zero-energy identities.
* Global counting inequalities.

A previous aggregation formula required correction because its indexing did not preserve the individual common differences.

The corrected formulation keeps the difference parameter explicit.

These results provide a foundation for further work on transferring information from all monochromatic pairs to a controlled range of distances.

The required distance-profile transfer has not yet been established.

3.5 Joint Rigidity of Three Sets

The Joint Rigidity program investigates whether three sets whose pairwise unions are all four-term-arithmetic-progression-free must satisfy stronger collective restrictions than those obtained from ordinary extremal bounds.

The project has established several local results, including:

* Local AP-avoidance characterizations.
* Structural restrictions within the designated $U$ region.
* Main-color six-position classifications.
* Extension constraints for monochromatic three-term progressions.
* Restrictions on two-color extensions.
* Five-position sliding-window constraints.

These results are local structural statements within their specified models.

The remaining difficulties include:

1. Controlling two-color extension escape.
2. Controlling overlaps between different progression extensions.
3. Establishing an effective lower bound for the relevant $D$ region.
4. Converting local extension restrictions into a global three-set deficit inequality.

The full Joint Rigidity theorem remains open.

4. Finite Hypergraph Certificates

The project also contains a separate finite combinatorial investigation under the designation CE-03b.

The fixed model uses $N=59$.

The documented work includes:

* Reduction to four-term arithmetic progression constraints.
* Construction of 37 witnesses.
* Identification of an empty $D$ region in the specified branch.
* Construction and indexing of 34 hyperedges.
* Independent-set certificates.
* Branch-by-branch finite verification.

An explicit independent-set witness is

$$
W_1={28,31,32,35,39}.
$$

Direct inspection of the indexed hyperedges establishes that no hyperedge is contained in this witness set, providing the required lower-bound certificate for the corresponding local independence-number argument.

The relevant finite audit has been frozen.

These certificates apply to their specified finite hypergraph model and do not automatically imply a theorem for arbitrary $N$.

5. Historical Model Reconstruction and Source Auditing

A substantial part of the project is devoted to distinguishing mathematical reconstruction from source-confirmed historical results.

G1 Historical Model

The current reconstruction records:

* Four templates $T_0,T_1,T_2,T_3$.
* Three associated scales.
* A 64-label configuration space.
* Several forbidden label-pair lists.

These items remain classified as partially recovered contextual information rather than fully source-confirmed definitions.

B2b-II Source Audit

The specified E3 source-coverage audit has been completed for its registered scope.

The recorded audit includes:

* Six source-audit sections.
* 24/24 checked items.
* 48/48 equation checks.
* 12 eliminated configurations.
* 12 conditional survivors.

These counts describe the audited scope only. They do not establish completeness of the entire historical model.

Missing original definitions and source materials remain explicitly marked as unresolved.

The project does not silently replace missing historical definitions with reconstructed formulas.

6. Zero-Density to Finite-Model Transformation

A separate mathematical development studies the relationship between a zero-point density formulation and a relaxed finite combinatorial model.

The project establishes the equivalence between the specified zero-point model and $F_3^{(\leq4)}$.

The corresponding identity is

$$
\boxed{\frac{F_3^{(\leq4)}(N)}{N}=1-\delta_4(N).}
$$

This provides an exact conversion between the two formulations.

The subsequent asymptotic extremal problem remains open.

The proved model-conversion result must therefore be distinguished from the unresolved asymptotic estimate.

7. Engagement with Existing Literature

The project also studies published and publicly available work on related arithmetic-progression coloring problems.

Relevant research directions include:

* Behrend-type constructions.
* Bounds for progression-free sets.
* Arithmetic-progression coloring bounds.
* Carry-control methods.
* Structural and energy-based approaches.

Particular attention has been given to the 2026 work of Shi and Dong, which establishes an upper bound of the form

$$
h(N)\leq N^{1/4+o(1)}
$$

under the relevant problem formulation.

The project has conducted a partial technical audit of the carry-control and endpoint conditions.

This audit is not claimed to be a complete independent reconstruction of the original proof.

Published results and their consequences are distinguished from original results developed within this project.

8. Research Governance and Verification Standards

A central principle of this project is that mathematical claims must retain their actual verification status.

The following distinctions are maintained:

| Status | Meaning |
|---|---|
| PROVED | A mathematical argument has been established within the specified assumptions. |
| VERIFIED | A specified finite or symbolic verification has passed. |
| LOCKED | A result or research record has been frozen against unapproved modification. |
| CONDITIONAL | A result depends on an explicitly stated unresolved assumption. |
| PARTIAL RECOVERY | Historical context has been reconstructed, but original sources are incomplete. |
| SOURCE GAP RETAINED | Required source material has not been located or confirmed. |
| OPEN / UNRESOLVED | The mathematical objective remains unsolved. |

The project follows several additional principles:

1. Local results are not automatically promoted to global theorems.
2. Finite computations are not treated as asymptotic proofs.
3. Reconstructed historical formulas are not represented as original source definitions.
4. Independent research branches retain separate assumptions and evidence.
5. Corrections and audit findings are preserved rather than silently overwritten.
6. Formal verification is not claimed unless the corresponding formal proof has actually been completed.

9. Current Open Problems

The principal unresolved objectives are:

Problem A — Three-Set Joint Rigidity

Establish a sufficiently strong joint deficit or energy inequality for three pairwise-disjoint sets whose pairwise unions are four-term-arithmetic-progression-free.

Problem B — Distance-Profile Transfer

Develop a rigorous transfer from unrestricted monochromatic pairs to a controlled set of arithmetic distances.

Problem C — Global Structural Closure

Convert the established local AP-extension restrictions into a global extremal theorem.

Problem D — Historical Source Recovery

Recover the missing original definitions and source materials required to validate the remaining historical model branches.

Problem E — Asymptotic Improvement

Determine whether the developed finite and structural methods can yield a stronger asymptotic lower bound for $h(N)$.

Problem F — Formal Verification

Develop a complete Lean formalization of the final mathematical argument, without sorry or admit.

10. Overall Assessment

As of November 28, 2026, this project has developed a substantial collection of finite combinatorial results, Pair-Union identities, local structural lemmas, energy estimates, hypergraph certificates, and source-audit records.

Its most significant mathematical direction is the investigation of three-set Joint Rigidity and the possibility of deriving stronger global restrictions from simultaneous pairwise arithmetic-progression avoidance.

Nevertheless, the complete Erdős #160 problem remains unresolved.

The project therefore presents its current achievements as an evolving mathematical research program rather than a claimed solution.

11. Attribution

Researcher: Hongzhao Zhang (张洪诏)
Research Team: DAZHuzhang. Art Team
Project Identifier: JSP-000158
Research Topic: Erdős Problem #160

This work is intended to provide a transparent and continuously auditable record of mathematical investigation, including proved results, finite certificates, partial reconstructions, unresolved assumptions, and future research objectives.

Research continues.

⸻

Last updated: November 28, 2026.
