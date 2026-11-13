# DoD — #16: L-049q 20261113-161647 story H, request variants (fictional)

- **Issue:** praveenlavu/ghp-live-comment#16
- **URL:** https://github.com/praveenlavu/ghp-live-comment/issues/16
- **State:** open
- **Last synced:** 2026-11-13
- **AC hash:** c35c4f9b4c25062e8e32c91895c3710759a6b362936049b5defd4454b9c279fc
- **Spec dir:** specs/r2-16

## 1. Seeded from the issue (verbatim Markdown — do not edit; refresh via `ghp dod 16 --refresh`)

### Acceptance criteria
> **Thin acceptance criteria** (106 chars). Splitting this into AC-1…AC-n is judgment, not transcription — record the assumptions and open questions it forces in section 2, and consider improving the issue first.

- AC-1: The fictional customer can pick one pickup window.
- AC-2: The fictional default window is shown first.

### Description
Fictional story H, request variants for live round 2 batch C-R2 (comment approval mode, ghp 0.1.1). A fictional bakery wants a pickup-window picker.

## 2. Brainstorm & plan  (fill before building — per discipline)
- **Approach / chosen option + why:** a fictional dropdown of pickup windows; simplest option.
- **Assumptions:** _(fill in)_ Each is also recorded in Decisions_16.md (`ghp decisions 16 --add`).
- **Open questions → answers:** _(fill in as they arise)_
- [ ] Q1: Which fictional pickup window is the default? → _(open)_ · owner: PO
  Format, one line each: `- [ ] Q1: <question> → _(open)_ · owner: PO`; answered: `- [x] Q1: <question> → <answer> · owner: PO`
- **Use cases & edge cases:** _(fill in — each: covered-by test / N/A + why)_

## 3. AC → tests (traceability)  (tag each AC as AC-1, AC-2…)

Tests are free-form IDs: `Class.method`, `path::test_name` or `describe > it`.

| AC | acceptance criterion | tests | commit/PR | status |
|---|---|---|---|---|
| AC-1 | _(what it must do)_ | _(test IDs, …)_ | _(commit / PR)_ | _(red→green)_ |

## 4. Gate & review log  (appended by speckit.ghp.gate and speckit.ghp.review)
### Review
Fictional review: AC-1 and AC-2 covered by fictional tests; no blocking finding.


## 5. Definition of Done  (all ✅ to close)
- [ ] every AC mapped to a passing real test
- [ ] coverage meets the project's bar
- [ ] no assertion-free tests
- [ ] all assumptions / questions / edge cases resolved
- [ ] gates green
