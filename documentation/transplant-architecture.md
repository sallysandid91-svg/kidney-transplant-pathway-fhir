# Kidney Transplant Care Pathway Architecture

```text
Patient
   │
   ├─────────────► Condition
   │                 (Chronic Kidney Disease)
   │
   ├─────────────► Encounter
   │                 (Nephrology Consultation)
   │
   ├─────────────► Observation
   │                 (Creatinine)
   │
   ├─────────────► Observation
   │                 (eGFR)
   │
   ├─────────────► Procedure
   │                 (Kidney Transplant)
   │
   └─────────────► MedicationRequest
                     (Tacrolimus)
```
