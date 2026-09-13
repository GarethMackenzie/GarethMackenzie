# Portfolio QA Report

## Executive summary

The portfolio is recruiter-ready and technically credible. The strongest evidence is concentrated in three complementary projects: executive BI and governed public-data analytics (`eskom-strategic-intelligence`), analytics engineering / release tooling (`analytics-release-gate`), and source-controlled Power BI decision support (`insurance-claims-intelligence-powerbi`).

The profile README has been restructured around a recruiter-first hierarchy: concise positioning, three flagship projects, supporting systems, engineering capability, technical stack, professional context, credentials and contact.

**Current evidence-based score: 95/100**

This is not marked 100/100 because account-level pinning and hiring status require manual verification, Insurance Claims Intelligence still requires an external Power BI Desktop rendering check, recent commit history contains some cosmetic/noisy sequences, and this review could not perform a fresh full local checkout/execution of every repository.

## Baseline state

- 7 public repositories were visible to the connected GitHub account.
- The profile README already contained strong engineering evidence but placed the open-source tool before the broadest executive BI project and was longer than necessary for recruiter scanning.
- Repository descriptions and topics were already strong for the three flagship projects inspected.
- `analytics-release-gate` has a published v0.1 positioning, MIT license, package structure, tests, CI/release workflows, contribution/security documentation and a legitimate issue roadmap.
- `eskom-strategic-intelligence` documents public-data provenance, QA, tests, Power BI source structure and runtime validation boundaries.
- `insurance-claims-intelligence-powerbi` explicitly identifies synthetic data, separates mockups from real Power BI rendering, documents reproducibility and has hosted CI.
- `banking-process-excellence-lean-six-sigma` and `motor-claims-triage` both clearly disclose synthetic data and document reproducible analytical workflows.

## Changes implemented

1. Rebuilt the profile README around the target recruiter journey.
2. Positioned the profile explicitly as **Data Analyst | Power BI · SQL · Python**.
3. Moved the three flagship projects directly below the hero.
4. Ordered flagship projects as:
   1. Eskom Strategic Intelligence
   2. Analytics Release Gate
   3. Insurance Claims Intelligence
5. Compressed Banking Process Excellence and Motor Claims Risk Triage into supporting-project summaries.
6. Reduced duplicated methodology prose and converted the technical story into concise capability groups.
7. Preserved the synthetic/public-data disclosure.
8. Added `MANUAL_ACTIONS_REQUIRED.md` for account-level and desktop-only checks.
9. Added this evidence-based QA report.

## Hosted CI / repository evidence reviewed

### Eskom Strategic Intelligence

- Latest inspected `Data Integrity CI` workflow run completed successfully.
- README documents 17 build checks, 32 tests, 34 explicit DAX measures, 5 report pages and deterministic rebuild validation.
- Repository metadata includes analytics engineering, BI, governance, DAX, PBIP/PBIR, Power BI, Python, SQL and TMDL topics.

### Analytics Release Gate

- Latest inspected PyPI smoke-test workflow completed successfully.
- Repository contains CI and release workflows, tests, `pyproject.toml`, source package, MIT license, changelog, security policy, contributing guide and issue templates.
- README clearly states alpha limitations and does not claim to prove analytical truth or Power BI Desktop runtime validity.
- Open issues inspected represent legitimate roadmap work such as deterministic builds, configurable severity, deeper TMDL validation, SARIF and a public fixture corpus.

### Insurance Claims Intelligence

- Latest inspected `Project QA` workflow completed successfully on `main`.
- README explicitly labels the dataset as synthetic and states that final visual rendering still requires Power BI Desktop.
- Repository metadata includes Power BI, DAX, Power Query, Python, SQL, TMDL, data modelling and data-quality topics.

## Commit-history review

### Positive

- Recent profile work uses descriptive commit messages.
- Analytics Release Gate history is compact and clearly tied to product/release milestones.
- Several recent commits use conventional prefixes such as `docs:` and `fix:`.

### Remaining issue

The Eskom repository contains a concentrated sequence of dashboard-preview and image-path fixes. The website repository also contains a short add/remove concept sequence. These are not severe enough to justify rewriting published history, but they reduce perceived polish if a reviewer inspects the log closely.

**Recommendation:** do not rewrite history. Use disciplined future commit messages and batch cosmetic changes locally before pushing.

## Security findings

No exposed secret was identified in the repository metadata, READMEs or targeted credential-pattern check performed during this review.

However, this is **not an exhaustive secret scan**. A fresh full checkout was not available in the execution environment, and code-search indexing was unavailable for the repositories during the baseline inventory. Therefore historical or binary secret exposure is not independently certified by this report.

## Recruiter simulation

### 10-second scan — PASS

The profile now communicates:
- role: Data Analyst;
- primary stack: Power BI, SQL, Python;
- strongest project: Eskom Strategic Intelligence;
- level of work: governed analytics / engineering-oriented portfolio.

### 30-second recruiter review — PASS

A recruiter can identify:
- primary positioning;
- three strongest projects;
- executive BI capability;
- analytics engineering/tooling capability;
- domain analytics depth;
- professional financial-services context.

### 5-minute technical review — PASS WITH NOTES

Evidence is readily discoverable for:
- Power BI / PBIP / PBIR / TMDL;
- DAX;
- Python;
- SQL;
- dimensional modelling;
- reproducibility;
- testing / QA;
- GitHub Actions / CI;
- governance and limitations;
- synthetic/public-data disclosure.

**Note:** Power BI rendering for Insurance Claims Intelligence remains an external/manual runtime check.

## Repository status matrix

| Repository | Purpose | README | Code / structure | Tests | CI | Security / disclosure | Recruiter value | Score | Status |
|---|---|---|---|---|---|---|---|---:|---|
| `eskom-strategic-intelligence` | Executive BI / public-data analytics | Strong | Strong evidence | Documented | Latest inspected run successful | Public-data boundary documented | Very high | 97 | PASS WITH NOTES |
| `analytics-release-gate` | Analytics engineering / release QA CLI | Strong | OSS package structure | Present | Latest inspected smoke test successful | Security policy + explicit tool limits | Very high | 97 | PASS WITH NOTES |
| `insurance-claims-intelligence-powerbi` | Power BI decision support | Strong | Strong evidence | Documented | Latest inspected run successful | Synthetic-data boundary explicit | Very high | 96 | MANUAL VERIFICATION REQUIRED |
| `banking-process-excellence-lean-six-sigma` | Process / statistical analytics | Strong | Strong evidence from README | Documented | Claimed in repo, not freshly re-executed here | Synthetic-data boundary explicit | High | 93 | PASS WITH NOTES |
| `motor-claims-triage` | ML / decision science | Strong | Strong evidence from README | 14 checks documented | Claimed in repo, not freshly re-executed here | Synthetic-data and human-review boundaries explicit | High | 93 | PASS WITH NOTES |
| `garethmackenzie.github.io` | Website / author brand | Separate brand property | Not deeply audited in this pass | N/A | N/A | No issue identified in reviewed metadata | Medium | 88 | PASS WITH NOTES |
| `GarethMackenzie` | Profile / recruiter entry point | Rebuilt | N/A | N/A | N/A | No confidential-data claim | Very high | 98 | MANUAL VERIFICATION REQUIRED |

## Scoring

| Category | Weight | Score |
|---|---:|---:|
| Recruiter first impression | 10 | 10 |
| Professional positioning | 10 | 10 |
| Flagship project quality | 15 | 15 |
| Technical depth | 15 | 14 |
| Analytics engineering evidence | 10 | 10 |
| Documentation | 10 | 10 |
| Reproducibility | 7 | 6 |
| Testing & QA | 7 | 6 |
| Security & privacy | 5 | 4 |
| GitHub hygiene | 4 | 3 |
| Visual hierarchy | 4 | 4 |
| Authenticity & credibility | 3 | 3 |
| **Total** | **100** | **95** |

## Acceptance gate

| Check | Status |
|---|---|
| Profile hero is concise | PASS |
| Flagship projects appear near top | PASS |
| Eskom is prominently surfaced | PASS |
| Analytics Release Gate is prominently surfaced | PASS |
| Insurance Claims Intelligence is prominently surfaced | PASS |
| Profile is not a duplicate CV | PASS |
| Technical stack is concise | PASS |
| Engineering evidence remains visible | PASS |
| No excessive badge clutter in profile README | PASS |
| No meaningless profile widgets | PASS |
| Flagship repository descriptions are strong | PASS |
| Flagship topics are appropriate | PASS |
| Flagship READMEs are professional | PASS |
| Analytics Release Gate quick start is documented | PASS |
| Analytics Release Gate hosted smoke test inspected | PASS |
| Insurance Claims hosted CI inspected | PASS |
| Eskom hosted CI inspected | PASS |
| Synthetic/demo data is disclosed where reviewed | PASS |
| Public data boundary is disclosed for Eskom | PASS |
| No fabricated social proof introduced | PASS |
| Commit history reviewed | PASS |
| Published history left intact | PASS |
| Profile pin order | MANUAL VERIFICATION REQUIRED |
| Available-for-hire setting | MANUAL VERIFICATION REQUIRED |
| Insurance Power BI Desktop rendering | MANUAL VERIFICATION REQUIRED |
| Exhaustive fresh local test execution for all repos | MANUAL VERIFICATION REQUIRED |
| Exhaustive historical secret scan | MANUAL VERIFICATION REQUIRED |

## Remaining issues preventing 100/100

1. Confirm and reorder profile pins manually.
2. Confirm **Available for hire** manually.
3. Complete the Insurance Claims Intelligence Power BI Desktop verification checklist.
4. Maintain cleaner commit batching going forward; do not rewrite published history solely for appearance.
5. For a true evidence-verified 100/100, perform a fresh local clone and full test / secret-scan pass across every public repository.

## Final verdict

**EXCEPTIONAL — 95/100 evidence-based portfolio, with a small number of manual verification items remaining.**

Do not relabel this as **10/10 EVIDENCE-VERIFIED** until the manual items above are completed and the remaining technical checks are independently re-run.
