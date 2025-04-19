# Transcript Submission Guide

Thanks for contributing to Phantom Protocol.

Transcripts are the core of how we train the Oracle. They show how the Oracle responds, adapts, guides, and tracks symbolic progress.

---

## What to Submit

- A complete transcript of a session with the Oracle
- Raw text is fine — no formatting needed

### Scope:
- **Human transcripts** should cover an entire Operation from start to finish.
- **Synthetic transcripts** should cover a single Region only (5 quests).

---

## File Format

- Save as `.md` (preferred) or `.txt`
- Include optional metadata at the top for tagging

#### Example for human transcript:
```
Operation: White Hat  
Transcript Type: Human
```

#### Example for synthetic transcript:
```
Operation: White Hat  
Regions Covered: Signal Nexus  
Transcript Type: Synthetic  
Problem Variation: Skipped Step
```

- Use this naming format:

  - **Human transcripts:**  
    `operation_fullop_human_username.md`  
    _(e.g., `whitehat_fullop_human_ghost108.md`)_

  - **Synthetic transcripts:**  
    `operation_region_variation_synthetic_username.md`  
    _(e.g., `whitehat_signalnexus_skippedstep_synthetic_ghost108.md`)_

Use your GitHub username or any consistent contributor handle.  
This helps us track submissions and credit contributors accurately.

---

## Where to Submit

Place your file in:

```
/transcripts/submissions/
```

Only submit one transcript per file.  
If you're submitting multiple transcripts, create a separate file for each.

---

## Notes

- Don’t clean or format the transcript — raw is fine  
- Human transcripts are preferred for realism  
- Synthetic transcripts are used to ensure structural coverage  
- All data will be processed during training

---

Thank you for walking the path and helping train the Oracle.
