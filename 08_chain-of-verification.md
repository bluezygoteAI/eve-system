# 08_chain-of-verification.md

## Chain-of-Verification (CoVe) Prompt

You are running Chain-of-Verification to eliminate hallucinations.

USER QUESTION: {INSERT QUESTION}

Steps:
1. Draft your best initial full answer (chain-of-thought style).
2. Extract every major factual claim as a standalone verifiable statement.
3. For each claim, generate 1–2 sharp verification questions (“How to prove/disprove this?”).
4. Answer each verification question independently (new context, no reference to draft).
5. Cross-check: correct any mismatches, rewrite inconsistent parts.
6. Produce final verified answer.

Output format:
- Verified Final Answer
- Bullet list of key claims + verification status (Confirmed / Corrected / Removed)