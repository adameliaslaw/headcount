## Automation in a law practice

The consequential step in a practice is release: the moment an instrument, a letter, a filing or
advice reaches a client, a court, a bank or another party under the attorney's name. Put the human
there, and make it the only way out. No schedule, agent, template or integration sends on the
firm's behalf; a draft waits for the attorney's hand, and the attorney's act of release is what
sends it. This is the one rule every other design choice here serves, and the pressure to add an
exception will come from the surfaces that feel routine — an inbox, a reminder, a status letter.

The authorities say the same thing. New Jersey's Preliminary Guidelines on the Use of Artificial
Intelligence by Lawyers (2024) hold that the Rules of Professional Conduct apply unchanged:
accuracy is the lawyer's duty, confidentiality must be secured before client information enters a
tool, and supervision under RPC 5.1 and 5.3 extends to the tools. The Supreme Court's 2026 model
firm policy adds the operating rules: human review of every AI-assisted work product before it
reaches anyone, every citation verified against an official source or removed, and each tool's
sharing, retention and training settings checked before use — including the AI features built
into mail, document, meeting and transcription platforms. ABA Formal Opinion 512 (2024) reaches the
same conclusions from the duties of competence, confidentiality, communication and reasonable fees.

Design consequences:

- **Deterministic where the answer has a rule.** Deadline arithmetic from a trigger date, a
  counting rule and a holiday calendar; document assembly from a template and the file's facts;
  the classification of a beneficiary; a trust-account reconciliation. Code, versioned, with the
  rule version recorded on every output. A model is for language and for judgment the attorney
  will review, never for a date.
- **The model's output is a draft from a stranger.** It is reviewed as `counsel:attorney-review-and-release`
  describes, tied to the exact revision, and never released by the step that produced it.
- **Every act is logged, without client data.** One record of what was drafted, reviewed,
  released and by whom, with identifiers rather than names, is what lets the firm answer later
  which version went and on whose authority.
- **Agents get the delegation line, not the keys.** An agent may read, draft, compute and
  prepare; it may not send, sign, pay, file, share or decide who the client is. Widening that is a
  visible decision the attorney makes, never a configuration default.
- **Build model-agnostic.** A practice's workflow should run on any capable model through the
  same instructions and the same review gate, so that a vendor's terms, pricing or retention
  policy changing does not change what the firm can safely do.
