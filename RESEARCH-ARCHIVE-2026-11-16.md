# Erdős Problem #160 — Research Archive

**Project ID:** JSP-000158  
**Researcher:** Hongzhao Zhang (张洪诏)  
**Research status:** OPEN / UNRESOLVED  
**Archive update:** 16 November 2026  
**Repository:** <https://github.com/zhang0004-prog/JSP-000158-Erdos-Problem-160>

## Scope and status

This repository is a research archive for Erdős Problem #160. It records finite extremal results, proof manuscripts, structural investigations, computational enumerations, and literature-audit obligations.

The original problem is not claimed to be solved. The results below are scoped statements about specific finite models, enumerations, or proof projects. A finite result or partial lemma must not be read as an asymptotic solution of the original problem, an award claim, or independent external verification.

The archive distinguishes:

- **SEALED / VERIFIED (project ledger):** a result the researcher has formally accepted and frozen within the stated scope.
- **SOURCE_CONFIRMED:** a statement confirmed against an identified source.
- **SOURCE_LOCATED:** a source has been found, but the relevant claim has not necessarily been fully checked.
- **OPEN / UNRESOLVED:** the proof or audit is incomplete.
- **NOT_ESTABLISHED:** available evidence does not establish the claim.
- **NOT_LOCATED:** a particular search location did not contain the item; this is not a claim that the item does not exist elsewhere.
- **SOURCE_GAP_RETAINED=TRUE:** missing source evidence remains explicitly unresolved.

“Sealed” describes the status in the research ledger; it does not by itself mean peer-reviewed, independently reproduced, formally verified in Lean, or accepted by an external body.

## Problem convention

The strong coloring problem tracked here asks for a coloring of \([N]\) in which every nontrivial 4-term arithmetic progression uses at least three distinct colors. This is kept distinct from weaker or differently formulated progression-avoidance conditions, including the ABBA/ABAB distinctions appearing in related literature.

The exact definition used in any individual computation or lemma must be read from that item’s specification. Results from different models (number of colors, progression convention, endpoints, or scale set) are not silently transferred between one another.

## Research results and workstreams

### 1. The \(N=16\) three-term-progression extremal result

**Project record:** `N16_EXTREMAL_PROOF_COMPILATION_V2`  
**Ledger status:** `SEALED_AND_VERIFIED` (researcher-accepted static proof compilation)  
**Recorded conclusion:** \(r_3(16)=8\).

The compiled static proof package records:

- a balanced \(4+4\) split;
- 25 legal templates;
- Type-I and Type-II cross-half 3-AP compatibility criteria;
- 50 ordered compatible pairs, partitioned as \(25+14+11\);
- the weight distribution \(W=6:8\), \(W=5.5:34\), \(W=5:8\);
- maximum weight 6.

This is a finite auxiliary extremal result concerning \(r_3(16)\). It is not, by itself, a solution of Erdős Problem #160. Historical source archives and the original `ARCHIVE_A` / `ARCHIVE_B` materials are to remain unchanged.

### 2. Seven-element subextremal audit at \(N=16\)

**Project:** `N16_7ELEMENT_SUBEXTREMAL_AUDIT`  
**Stage 3, Step 2:** CORE-BAND ANALYSIS — accepted and sealed in the research ledger.

Recorded audit outputs:

- 164 global configurations and 82 orbits;
- position-frequency accounting for all 16 orbit classes, with 0/1/2 counts closed;
- total position occurrences: 1,148;
- reflection symmetry: \(F(x)=F(17-x)\).

This is a separate structural audit branch. It must not be conflated with the proof of \(r_3(16)=8\). The parent project’s sealed report remains immutable.

### 3. Binary modular-period analysis

The frozen B6 modular-period work records three modes for even \(m=2q\):

- \(\alpha=1101\);
- \(\beta=1011\);
- \(\gamma=0110\).

The ledger includes modal-count identities and a hand-proof chain connected to the \(N=12\) extremal bound. These statements are restricted to the model and hypotheses in the underlying frozen memorandum; they are not asserted for arbitrary colorings or unrelated scale systems.

### 4. Multiplicative-scale compatibility counts

The fixed-endpoint compatibility enumeration records:

- 7,566 realizable six-tuples;
- extension counts in \(\{7,13,17,21\}\);
- frequencies 2,688, 3,504, 936, and 438, respectively;
- minimum 7 and maximum 21;
- mean \(89{,}478/7{,}566\).

These are finite enumeration statistics for the specified multiplicative-scale model. The exact input specification and enumeration record should accompany any independent reproduction.

### 5. Fourteen-scale binary extension identity

For a legal 12-scale prefix \(\pi\), the frozen binary-model identity is

\[
E_{14}(\pi)=\sum_{w\in\{0,1\}} n(w,a_{288})n(w,a_{432}),
\qquad
n(w,t)=
\begin{cases}
1,&w=t,\\
2,&w\ne t.
\end{cases}
\]

Consequently, \(E_{14}=5\) when \(a_{288}=a_{432}\), and \(E_{14}=4\) otherwise.

**Scope restriction:** this result is for the binary (two-colour) model only and is deliberately isolated from the twelve-scale ledger. It is not a statement about the unrestricted strong problem.

### 6. Finite three-colour 4-AP enumeration

For the specified finite coloring model:

- at \(N=12\), the enumeration records 6 valid configurations;
- at \(N=13\), it records 0 valid configurations;
- the corresponding numbers of nontrivial 4-AP constraints are 18 and 22.

The recorded consequence under that exact target definition is \(h(N)\ge 4\) for \(N\ge 13\), by restriction to the first 13 positions. This is a finite lower-bound result, not an asymptotic solution.

### 7. Finite four-colour enumeration

For the specified four-colour model:

- \(N=22\): 144 valid configurations, all using four colours, represented by 6 canonical representatives under colour permutations;
- \(N=23\): no valid configurations;
- \(N=21\): 4,272 valid configurations and 178 canonical representatives;
- among the \(N=21\) representatives, 14 are strictly 7-periodic, and none of those extends to \(N=22\); only 5 of the 178 representatives extend.

The symmetry audit uses colour permutations and reversal \(x\mapsto 23-x\), with group size 48. The recorded finite conclusion is \(h(22)=4\) and \(h(N)\ge 5\) for \(N\ge 23\), subject to the exact coloring definition and exhaustive-enumeration specification.

These finite counts do not establish an asymptotic bound. Canonical representatives and hashes should be checked against the associated raw enumeration artifacts before being treated as independently reproduced.

### 8. C4 local-repair investigation

The latest corrected ledger records:

- 45 baseline violating windows;
- maximum disjoint family size \(\nu=5\);
- an `EXACT5` candidate space of \(4^5\cdot 3^5=248{,}832\);
- 36 `AP10-XOR` skeletons reduced to 12 zero-cover skeletons, which are recorded as excluded;
- 23 residual skeletons remain OPEN.

Current unconditional lower-bound status in this branch: at least 5. A lower bound of at least 6 has not been re-established in the latest corrected ledger and must not be claimed.

The next suggested audit targets in the working notes include `SKEL_02` and `SKEL_03`, but no automatic restart or new derivation is authorized by this archive entry.

### 9. Pair-union averaging

The recorded identity is

\[
\sum_{i<j}|C_i\cup C_j|=(k-1)N,
\]

with the associated bound

\[
h(N)\ge \left\lceil\frac{2N}{r_4(N)}\right\rceil
\]

under the hypotheses of the underlying argument. Further asymptotic improvements and stronger cross-colour joint inequalities remain open.

## Literature and source audit

The literature audit is deliberately not represented as complete.

- **Shi–Dong, arXiv:2607.20752v2:** the paper’s claimed upper bound \(h(N)\le N^{1/4+o(1)}\) is recorded as source-confirmed in the research notes; the full audit remains pending.  
  <https://arxiv.org/abs/2607.20752>
- **Raghavan, arXiv:2603.27045v3:** the notes track the Theorem 1.4 route using \(M=\lfloor 2N/3\rfloor\) and a truncation argument. Lemma 4.4 remains pending; `RAGHAVAN_FULL_PROOF` is not complete.  
  <https://arxiv.org/abs/2603.27045>
- **Deng–Tidor–Zhao, arXiv:2307.06914v2:** the audit distinguishes ABBA from ABAB and flags the condition \(\gcd(M,24)=1\) in the Lemma 7.11 audit.  
  <https://arxiv.org/abs/2307.06914>
- **Ruzsa (1993), Theorem 2.3, p. 263:** the research notes record that the proof is suppressed in the article. The omitted proof is not reconstructed or treated as source-present.  
  `AUTHOR_PROOF_OMISSION=SOURCE_CONFIRMED`; `PROOF_IN_1993_ARTICLE=ABSENT`.

A source being located or a claim being recorded as source-confirmed does not imply that every dependent lemma, transfer, or proof has been audited.

## Archive integrity and authorization boundaries

- The original repository files dated 10 November 2026 are historical records and must not be overwritten.
- The parent `N16_7ELEMENT_SUBEXTREMAL_AUDIT` and its final sealed report are immutable.
- `N16_ARCHIVE_BYTE_VERIFICATION_01` is a read-only evidence-recovery project: locate original external archives, record metadata and SHA-256, losslessly parse T/M templates and the 82-pair compatibility list, and compare them with the recovered conversation set.
- That recovery scope does not authorize new derivations, code execution, SAT/DRAT/checker work, or automatic branch restart.
- P5 source files previously sought were `NOT_LOCATED` in the checked sandbox location only. This is not evidence that they do not exist elsewhere.
- No Lean formalization, independent external reproduction, or third-party certification is claimed here unless separately documented with source evidence.

## AI-use disclosure and attribution references

The following wording is reproduced as guidance from the named public prize documents. It is not represented as a verified transcription of the project’s original homepage charter.

**Justin Sun Prize FAQ, Q6 — AI disclosure:**

> AI or automated tools may participate in analysis and verification,
> but do not independently dictate award decisions. AI-generated
> evaluations serve strictly as supporting references and do not
> independently determine an award. The Organizing Committee makes final
> evaluation decisions in accordance with the Selection Rules and
> retains authority over all award approvals.

Source: <https://www.hejustinsun.com/prize/faq>

**Participation and Claiming Process, §2.2 — Attribution:**

> Under Attribution, identify the solver and their contribution, any
> independent verifier, and public authorship evidence, such as the
> paper’s author list, an announcement by the author or project, or
> another public attribution source.

Source: <https://www.hejustinsun.com/prize/participation>

This repository is a public research archive, not an award application or claim of eligibility. Any future submission must follow the current official rules and accurately identify contributions and independent verification.

## Open obligations

1. Complete the pending literature audits without upgrading unverified intermediate steps.
2. Recover and byte-verify original archive artifacts under the explicitly read-only `N16_ARCHIVE_BYTE_VERIFICATION_01` scope.
3. Preserve all unresolved C4 skeletons and the current lower-bound limitation.
4. Publish raw specifications, source files, hashes, and reproducibility records before making stronger computational-verification claims.
5. Keep the original problem status OPEN / UNRESOLVED until a complete proof is established.

---

This README is an index and status summary. The underlying proof manuscripts, specifications, raw data, and audit logs control whenever a detail requires finer scope or qualification.
