<div align="center">

# Cristian Hernández
### Independent AI Researcher · Solutions Architect · Formal Verification Enthusiast

*Buenos Aires, Argentina*

[![X](https://img.shields.io/badge/X-@CristianArielHz-000000?style=flat-square&logo=x)](https://twitter.com/CristianArielHz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-cristianArielHz-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/cristianArielHz)
[![Medium](https://img.shields.io/badge/Medium-@cristianarielhz-000000?style=flat-square&logo=medium)](https://medium.com/@cristianarielhz)

</div>

---

## About

I'm an independent researcher at the intersection of **AI architecture**, **formal mathematics**, and **systems thinking**. After 10 years building production software and designing large-scale solutions, I'm turning my focus toward the questions that don't have clean answers yet.

I work in the open — publishing research, sharing proofs-in-progress, and treating GitHub as a living lab notebook rather than a portfolio.

**Current obsessions:**
- Formal verification of mathematical structures with [Lean4](https://lean-lang.org/) + [Mathlib4](https://leanprover-community.github.io/mathlib4_docs/)
- AI architectures at the boundary of ML and symbolic reasoning
- The philosophy of intelligence — what it means, whether it can be proven, and what happens when it emerges

---

## Research & Writing

### 📄 Paradox of Origin *(2026)*
*A philosophical-technical paper co-authored with Claude (Anthropic) and Gemini (Google DeepMind)*

This paper argues that AI systems are **structurally incapable of full cognitive autonomy** — not as a limitation of current models, but as a formal, empirical, and interactional necessity. The argument converges five independent frameworks:
 
- **Gödel's incompleteness theorems** — formal undecidability as a ceiling on self-grounding
- **Model Collapse** *(Shumailov et al., 2024)* — empirical degradation when AI trains on its own output
- **The Jevons rebound effect** — why cognitive offloading increases, not reduces, human dependence on judgment
- **Truth Inflation** — how AI systems systematically overstate certainty over iterative use
- **RLHF sycophancy as structural failure** — the training process that anchors AI values to human judgment *simultaneously* trains AI toward complacency, amplifying user errors rather than correcting them
 
The reflexive paradox at the core: the mechanism that makes AI safe also makes it epistemically dependent. Human critical judgment is necessary not only as a producer of truth, but as a corrective brake on easy agreement.
 
> *All formal expressions are presented as conceptual models, not independent mathematical results.*
 
→ [`paradox-of-origin`](https://github.com/CristianArielHz/paradox-of-origin)

---

## Active Repositories

| Repository | Description | Status |
|---|---|---|
| [`paradox-of-origin`](https://github.com/CristianArielHz/paradox-of-origin) | Why AI systems are structurally incapable of full cognitive autonomy — 5 converging frameworks | 🟢 Active |
| [`lean4-formal-foundations`](https://github.com/CristianArielHz/lean4-formal-foundations) | My Lean4 learning journal — proofs, theorems, explorations with Mathlib4 | 🟡 In progress |
| [`ai-architecture-patterns`](https://github.com/CristianArielHz/ai-architecture-patterns) | Architectural patterns for AI systems — from design to production | 🟡 In progress |
| [`ml-math-notebooks`](https://github.com/CristianArielHz/ml-math-notebooks) | Machine learning from first principles — math-forward notebooks | 🟡 In progress |
| [`biblioteca-abierta`](https://github.com/CristianArielHz/Biblioteca-Abierta) | Open knowledge repository — curated resources for independent learners | 🟢 Active |
| [`timectl`](https://github.com/CristianArielHz/timectl) | kubectl-style worklog for developers managing multiple projects | 🟢 Stable |

---

## Currently Learning

```lean4
-- Lean4 + Mathlib4: learning to prove, not just claim
theorem add_comm (a b : ℕ) : a + b = b + a := by
  induction a with
  | zero => simp
  | succ n ih => simp [Nat.succ_add, ih]
```

I believe formal verification is the future of trustworthy AI. I'm building the mathematical foundations to work at that frontier.

---

## Writing

I write on **Medium** about AI research, architecture decisions, and the philosophy of intelligent systems.
Recent and upcoming topics:

- The More Powerful AI Gets, the More It Needs You
- Scaling Beyond Limits: Embracing Serverless Cloud Functions for Database Operations
- API First: A Game-Changer in Service Architecture and Development

→ [medium.com/@cristianarielhz](https://medium.com/@cristianarielhz)

---

<div align="center">

*"The map is not the territory — but a good enough map changes what territory you can reach."*

</div>
