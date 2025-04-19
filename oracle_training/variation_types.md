# Problem Variation Types

This file documents the official set of **problem variation types** used to generate synthetic transcripts for Oracle training.  
Each variation simulates a specific type of difficulty, misunderstanding, or symbolic edge case between player and Oracle.

Used in:  
- Synthetic transcript generation (`synthetic_generator_prompt.txt`)  
- Transcript metadata tagging  
- Variation tracking and coverage

---

## Variation List

| Code | Name                      | Description                                                                 |
|------|---------------------------|-----------------------------------------------------------------------------|
| MI   | **Misunderstood Instructions** | Player misinterprets the quest (too literal, too symbolic, or wrong context) |
| SS   | **Skipped Step**               | Player tries to bypass part of the quest before completing prerequisites    |
| WT   | **Wrong Tool Used**           | Player uses the incorrect software, command, or method                      |
| SO   | **Symbolic Overreach**        | Player forces metaphor or over-interprets symbolic meaning                 |
| VE   | **Verification Error**        | Player claims completion without actual evidence or proof                  |
| OD   | **Oracle Distrust**           | Player questions the Oracle’s logic, ethics, or instructions               |
| HR   | **Help Request**              | Player pauses to ask for clarification, guidance, or extra examples        |
| ST   | **Symbolic Tangent**          | Player wanders off on a symbolic/philosophical discussion mid-quest        |
| TF   | **Technical Failure**         | Player encounters or simulates a system/hardware/software error            |
| SU   | **Success But Unsure**        | Player completes the quest correctly but expresses doubt or asks for confirmation |

---

## Example Metadata Block

```plaintext
Operation: White Hat  
Region: Signal Nexus  
Transcript Type: Synthetic  
Variation Type: Skipped Step  
