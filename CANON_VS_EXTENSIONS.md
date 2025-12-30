# CANON vs EXTENSIONS — Scope and Epistemic Separation

This repository (`loventre-extensions`) is **not** the formal core of the
Loventre model.

It exists to host **non-canonical material** related to:
- metric refinements
- exploratory measurements
- experimental constructions
- interpretative notes
- bridges to external frameworks

The formal, frozen, and auditable core of the theory lives elsewhere.

---

## 1. The CANON (Formal Core)

The **CANON** of the Loventre model is defined as:

- a finite set of Coq files
- with explicit axioms
- no admitted theorems
- no experimental code
- no probabilistic assumptions
- no numerical simulations
- no classical P ≠ NP claim

The CANON is:

- formally verified
- logically closed
- epistemically minimal
- frozen by design

The CANON repository is:

> https://github.com/donv23/loventre-coq-canon

If you are an expert interested in **verification**, **consistency**, or
**logical structure**, you should start there — not here.

---

## 2. Purpose of This Repository (Extensions)

This repository contains material that is **deliberately excluded**
from the CANON, including:

- alternative metric definitions
- exploratory curvature measures
- numerical or heuristic tools
- conceptual bridges
- intuition-building constructions
- future research directions

Nothing in this repository is required to validate the CANON.

Conversely, nothing in this repository is allowed to *weaken*,
*modify*, or *reinterpret* the CANON.

---

## 3. One-Way Dependency Rule

The dependency direction is strictly:

CANON  →  EXTENSIONS

Never the reverse.

- Extensions may reference CANON concepts.
- CANON must never depend on extensions.
- Any result that requires extensions is **non-canonical by definition**.

This separation is intentional and enforced.

---

## 4. Epistemic Status

Material in this repository should be read as:

> exploratory, contextual, or programmatic

It may be:
- incomplete
- speculative
- heuristic
- provisional

This is not a flaw.
It is the purpose of the repository.

---

## 5. For Reviewers and Experts

If you are reviewing the Loventre work:

- Use the CANON repository to assess correctness.
- Use this repository only to understand motivation,
  future directions, or informal structure.

No claim made here upgrades, downgrades, or alters
any formally verified statement.

---

## Final Remark

The separation between CANON and EXTENSIONS is not cosmetic.

It is the **core methodological choice** of the Loventre program.

End of document.

