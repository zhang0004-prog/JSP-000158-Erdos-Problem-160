# Erdős Problem #160 — Research Archive

Project ID: JSP-000158  
Researcher: Hongzhao Zhang (张洪诏)  
Research status: OPEN / UNRESOLVED  
Archive update: 16 November 2026

This repository is a research archive for Erdős Problem #160. It records finite extremal results, proof manuscripts, structural investigations, computational enumerations, and literature-audit obligations.

Important scope statement:

- The original problem is not claimed to be solved.
- The results recorded here are restricted to the exact finite models, definitions, and hypotheses specified in their corresponding work items.
- A finite result or partial lemma must not be read as an asymptotic solution of the original problem, an award claim, or independent external verification.
- A result marked as SEALED / VERIFIED describes the status in the research ledger; it does not itself imply peer review, independent reproduction, Lean formalization, or external certification.

The strong-coloring convention tracked in this archive is: every nontrivial 4-term arithmetic progression in [N] must use at least three distinct colors. This is kept distinct from weaker or differently formulated progression-avoidance conditions, including ABBA/ABAB distinctions appearing in related literature.

## Current status

The project remains OPEN / UNRESOLVED. The ledger is intentionally scoped and cautionary:

- no claim of a full solution to Erdős Problem #160;
- no transfer of finite-model conclusions across different definitions or scale systems;
- no upgrading of partial or intermediate claims to stronger global statements;
- all unresolved evidence gaps remain explicitly recorded.

## Research workstreams

### 1. N=16 three-term progression extremal result

The project record `N16_EXTREMAL_PROOF_COMPILATION_V2` records a researcher-accepted static proof compilation with the conclusion \(r_3(16)=8\). The package includes a balanced \(4+4\) split, 25 legal templates, compatibility criteria, and the stated weight distribution. This is a finite auxiliary extremal result for the specified model and is not, by itself, a solution of Erdős Problem #160.

### 2. Seven-element subextremal audit at N=16

The project `N16_7ELEMENT_SUBEXTREMAL_AUDIT` records a separate structural audit branch, including 164 global configurations, 82 orbits, position-frequency accounting, and reflection symmetry. This branch must not be conflated with the proof of \(r_3(16)=8\).

### 3. Binary modular-period analysis

The frozen B6 modular-period work records three modal cases for even \(m=2q\), together with identities and a hand-proof chain restricted to the model and hypotheses of the underlying memorandum. These statements are not asserted for arbitrary colorings or unrelated scale systems.

### 4. Multiplicative-scale compatibility counts

The fixed-endpoint compatibility enumeration records 7,566 realizable six-tuples, extension counts in \(\{7,13,17,21\}\), the corresponding frequencies, and the stated mean value. These are finite enumeration statistics for the specified multiplicative-scale model.

### 5. Fourteen-scale binary extension identity

The frozen binary-model identity records an exact finite relation for a legal 12-scale prefix, with the corresponding finite consequence when the parameters coincide or differ. This result is intentionally isolated to the binary two-colour model and is not a statement about the unrestricted strong problem.

### 6. Finite three-colour 4-AP enumeration

For the specified finite coloring model, exhaustive enumeration records valid configurations at N=12 and N=13, together with the corresponding nontrivial 4-AP constraints. The obtained consequence is finite and restricted to the exact target definition; it does not constitute an asymptotic solution.

### 7. Finite four-colour enumeration

For the specified four-colour model, the archive records finite valid configurations at N=21, N=22, and N=23, together with canonical representatives and the stated symmetry audit. The recorded finite conclusion is \(h(22)=4\) and \(h(N)\ge 5\) for \(N\ge 23\), subject to the exact coloring definition and exhaustive-enumeration specification. These counts do not establish an asymptotic bound.

### 8. C4 local-repair investigation

The latest corrected ledger records 45 violating windows, a maximum disjoint family size of \(\nu=5\), an `EXACT5` candidate space of size \(4^5 \cdot 3^5 = 248{,}832\), and 23 residual skeletons remaining OPEN. The current unconditional lower-bound status in this branch is at least 5; a lower bound of at least 6 has not been re-established in the latest corrected ledger.

### 9. Pair-union averaging

The archive records a pair-union identity and the associated lower-bound expression under the hypotheses of the underlying argument. Further asymptotic improvements and stronger cross-colour joint inequalities remain open.

## Literature and source audit

The literature audit is deliberately not complete. The archive records source-confirmed and source-located statements, including the Shi–Dong, Raghavan, Deng–Tidor–Zhao, and Ruzsa items listed in the project notes. A source being located or a claim being recorded as source-confirmed does not imply that every dependent lemma, transfer, or proof has been audited.

## Archive integrity and authorization boundaries

- Historical repository files dated 10 November 2026 are preserved and must not be overwritten.
- Parent sealed audit records remain immutable.
- `N16_ARCHIVE_BYTE_VERIFICATION_01` is a read-only evidence-recovery project intended to locate original external archives, record metadata and SHA-256 values, and compare recovered artifacts against the recorded conversation set.
- This scope does not authorize new derivations, code execution, SAT/DRAT/checker work, or automatic branch restart.
- Previously sought P5 source files were NOT_LOCATED in the checked sandbox only; this does not imply that they do not exist elsewhere.
- No Lean formalization, independent external reproduction, or third-party certification is claimed unless separately documented with source evidence.

## AI-use disclosure and attribution references

The following wording is reproduced as guidance from the named public prize documents and is not represented as a verified transcription of the project’s original homepage charter.

> AI or automated tools may participate in analysis and verification, but do not independently dictate award decisions. AI-generated evaluations serve strictly as supporting references and do not independently determine an award.

Source: https://www.hejustinsun.com/prize/faq

> Under Attribution, identify the solver and their contribution, any independent verifier, and public authorship evidence.

Source: https://www.hejustinsun.com/prize/participation

This repository is a public research archive, not an award application or claim of eligibility. Any future submission must follow the current official rules and accurately identify contributions and independent verification.

## Open obligations

1. Complete the pending literature audits without upgrading unverified intermediate steps.
2. Recover and byte-verify original archive artifacts under the read-only recovery scope.
3. Preserve unresolved C4 skeletons and the current lower-bound limitation.
4. Publish raw specifications, source files, hashes, and reproducibility records before stronger computational-verification claims are made.
5. Keep the original problem status OPEN / UNRESOLVED until a complete proof is established.

---

This README is an index and status summary. The underlying proof manuscripts, specifications, raw data, and audit logs control whenever a detail requires finer scope or qualification.
