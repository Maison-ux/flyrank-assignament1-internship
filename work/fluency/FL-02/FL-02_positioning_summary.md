# FL-02 — Positioning Summary

## 1. Claim

I can build AI systems that turn model predictions into usable,
confidence-aware decision-support outputs.

## 2. Target Person

A founder of a small healthtech startup who needs to make risk or
triage decisions from imperfect data.

## 3. Desired Action

Hire for a paid pilot.

## 4. Verified Evidence

- ECG image preprocessing and CNN model training/evaluation
- Six-class ECG classification
- A confidence score (highest softmax probability) computed and displayed alongside the predicted class

## 5. Explicitly Not Claimed

- Uncertainty quantification or calibration
- Conditional/threshold behavior on confidence
- Executable dashboard
- Persistent historical record-keeping
- Real-world validation, deployment, or clinical outcomes
- A user-facing application or automated workflow

## 6. Scope Note

All evidence above reflects the repository Maison directly controls
(`FIAP-TIAO-2026-CardioIA`, FASE4).

A separate version submitted by a teammate to FIAP may contain
additional features, but it is currently inaccessible. Its
capabilities are therefore treated as unknown and are excluded from
the claim until independently verified.

## 7. Next Concrete Step

Rewrite the CardioIA README using only the verified evidence above,
scoped to the ECG classification model and displayed confidence score.
