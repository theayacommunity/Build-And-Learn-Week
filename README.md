# Build-And-Learn-Week
Welcome to the Build & Learn Week challenge hub — a beginner-friendly sprint to get into Web3 by building, shipping, and explaining small Rust smart contracts.

---

## Challenge Theme

🎯 **From Hello World to Real-World, Build our first Rust Smart Contract**

Participants will design, implement and explain a small but meaningful smart contract using Rust. Target runtimes are flexible — Solana, CosmWasm, Substrate-style abstractions or similar. Pick whichever you are comfortable with.

The challenge goals:

- Reinforce core Rust + smart contract fundamentals
- Encourage creative yet safe designs

---

## Core Challenge (Mandatory)

Build a Rust-based smart contract demonstrating these fundamentals:

- State initialization
- Controlled state mutation
- Access control
- Error handling
- Basic security considerations

Allowed scope (beginner-friendly): implement one of the following (or propose an equivalent), these are just examples you can pick from your side as well :

1. Token Vault
	- Users deposit tokens
	- Only the owner can withdraw
	- Includes balance tracking and authorization checks

2. Simple Escrow
	- Buyer locks funds
	- Seller can claim after a condition is met
	- Buyer can cancel before claim

3. On-chain Counter with Roles
	- Only specific roles can increment/decrement
	- Demonstrates ownership & permissions

4. Message Board / Registry
	- Users register messages or short data
	- Prevent overwrites without permission

Constraint: No external oracles or complex DeFi logic. Focus on correctness, clarity, and safety.

---

## Submission Requirements

> Each submission must include the following artifacts.

1. Rust smart contract code
	- Clean, commented, and readable
	- Idiomatic Rust (ownership, enums, Result-based errors)

2. `README.md` (project README — required)
	- What the contract does
	- Why the design was chosen
	- How state changes work (state machine / sequence)
	- What security checks are implemented
    - Deployed link

3. Short explanation (5–10 bullets)
	- Written as if explaining to a junior dev

4. Optional bonus items
	- Video Explaination/ Social media post
    - Unit / integration tests
	- Gas / compute considerations and measurements
	- Known limitations and possible improvements

---

## Prize Categories & Judging Criteria

Prizes are split into clear, creativity and so on for judges to score consistently.

### Best Overall Smart Contract

Judging criteria:
- Correctness, Creativity & completeness
- Clean Rust patterns and idiomatic code
- Clear access control and authorization
- Thoughtful error handling and explicit errors
- Well-documented logic and rationale

This category rewards the most audit-ready submission.

### Most Creative Smart Contract

Judging criteria:
- Novel idea within the allowed constraints
- Clear real-world analogy or interesting concept
- Still secure and understandable

Creativity > complexity.

### Best Real-World Utility

Judging criteria:
- Solves a real, relatable problem
- Could be extended toward production
- Clear user flow and purpose

Think: “Would someone actually use this?”

### Best Explained

Judging criteria:
- Crystal-clear explanations and mental models
- Easy for another beginner to understand

This category rewards communication and teachability.

### Best Social Post

Judging criteria:
- A concise X / LinkedIn post explaining what was built, why it matters and one learning takeaway
- Technical clarity without hype

---


## Submission Template (Quick — to copy into a PR)

Repository layout suggestion:

- `contract/` — Rust smart contract source
- `README.md` — project README (required)
- `SUBMISSION.md` — 5–10 bullet explanation 

Minimal `README.md` headings to include:

- Contract summary
- How to build & test
- State & flows (init, important transactions)
- Specify known limitations

---

## Judge Scorecard (Example)

Each judge can score entries 1–5 on these axes (sum used for ranking):

1. Correctness & completeness (1–5)
2. Rust idioms & code quality (1–5)
3. Access control & security checks (1–5)
4. Documentation & explainability (1–5)
5. Creativity / real-world utility (1–5)

---

Thank you for participating and staring your web3 journey.