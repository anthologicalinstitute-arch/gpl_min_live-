# THE REGISTER™
## GPL MIN Live™ — Sequence Intelligence and Audit Architecture

**Institution:** Anthological Institute for Research & Governance™  
**Research Program:** GPL™ Research  
**Project:** GPL MIN Live™  
**Document Status:** PROPOSED — BASELINE AUDIT REQUIRED  
**Classification:** Research and Engineering Specification

### 1. Purpose

Establish a controlled data architecture for recording, reconciling, and analyzing timestamped Fidelity portfolio observation sequences.

### 2. Scope

The Register™ will accommodate approximately 25–30 observation sequences and 11 research sleeves.

The system will preserve original source files and distinguish reported source information from calculated and independently verified results.

### 3. Register Architecture

The proposed architecture consists of:

1. Sequence Register — observation identification and chronology.
2. Holdings Register — individual position records.
3. Sleeve Register — sleeve-level classification and aggregation.
4. Change Register — differences between successive observations.
5. Market Signal Register — exploratory quantitative observations.
6. Audit Register — provenance, validation, and reconciliation history.

### 4. Source Integrity

For each supplied source file, record:

- Original filename.
- File format.
- File creation and modification metadata.
- Capture timestamp, where supported.
- Observation sequence identifier.
- Source provenance.
- Cryptographic file hash.
- Reconciliation status.

Original files must remain unmodified.

### 5. Evidence Classification

All findings must use the following classifications:

- REPORTED — information contained in source material.
- CALCULATED — results produced through documented calculations.
- VERIFIED — independently reconciled against sufficient supporting evidence.
- UNRESOLVED — incomplete, conflicting, or insufficient evidence.

### 6. Governance

No observation shall automatically constitute an investment recommendation, trading instruction, or validated predictive signal.

All model development remains subject to source reconciliation, methodological review, testing, and human authorization.

### 7. Acceptance Criteria

The initial specification is accepted for engineering review when:

1. The six registers are documented.
2. Source preservation requirements are defined.
3. Timestamp traceability is established.
4. Evidence classifications are standardized.
5. Audit requirements are documented.
6. Unresolved questions remain explicitly identified.

**Guiding Principle:**

Inquiry. Evidence. Human Responsibility.
