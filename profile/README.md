# Clarethium

The canonical methodology for AI-coupled work.

Clarethium publishes reference artifacts and tooling for measuring AI outputs, orienting operator practice, and sharpening craft. The work is open: reference texts under CC-BY 4.0, libraries under Apache 2.0. The discipline is canonical; the running implementations are reference-grade.

---

## Projects

**Open methodology reference artifacts:**

### [Lodestone](https://github.com/Clarethium/lodestone)

The canonical operator methodology for AI-coupled work. Eight sections plus a glossary specify the practice: stance, the loop, calibration, altitude, failure shapes, quality levels, surface discipline, and compound practice. The methodology operationalizes established traditions: naturalistic decision-making, reflective practice, cognitive load theory, deliberate practice, and extended cognition. A forward-looking annex on collective practice extends the discipline across operators (provisional, pending pilot validation).

### [Touchstone](https://github.com/Clarethium/touchstone)

Model-independent verification for AI-coupled work. The **Touchstone Standard** defines eleven measurement layers for output profiling and five layers for specification compliance verification. The `clarethium-touchstone` library is the reference implementation.

Domain: [touchstone.clarethium.com](https://touchstone.clarethium.com)

**Companion tooling:**

### [cma](https://github.com/Clarethium/cma)

Executable compound practice loop. The terminal-side companion to Lodestone. cma captures failures, surfaces relevant prior context at the moment of action, tracks decisions and rejected alternatives, and detects recurrence patterns. Action-time injection ships for Claude Code (PreToolUse and SessionStart hooks) and shell environments (zsh native preexec, bash via bash-preexec).

The companion **[cma-mcp](https://github.com/Clarethium/cma/tree/main/cma-mcp)** Python distribution exposes the same loop to MCP-compatible AI clients (Claude Desktop, Cursor, Cline, Continue.dev). Subprocess wrapper around the canonical bash cma binary; methodology-agnostic substrate; three-section payload (`analysis` + `agent_guidance` + `provenance`) on every response. Install with `pip install cma-mcp`.

**Applied vehicles:**

### [Frame Check](https://github.com/Clarethium/frame-check-mcp)

Applied tool for structural framing analysis. Names which perspectives a document takes, which it omits, how it positions the reader. The MCP package gives any MCP-compatible AI client (Claude Desktop, Cursor, Cline, Continue.dev) deterministic framing analysis as a tool.

Domain: [frame.clarethium.com](https://frame.clarethium.com)

---

## How the body composes

The four projects compose by design:

- **Lodestone** orients the operator's practice (the methodology canon).
- **Touchstone** validates work against quality standards (the measurement substrate).
- **cma** runs the compound practice loop on the operator's machine (the executable companion to Lodestone); **cma-mcp** is the same loop addressed to MCP-compatible AI clients.
- **Frame Check** applies Clarethium methodology in a specific context (frame validation).

The methodology and the running implementations reinforce each other: methodology refines from observed practice; practice runs better with surfaced context; measurement stays sovereign because it does not invoke models on the outputs being measured.

---

## What "model-independent" means

Most AI-evaluation tools use AI models to evaluate AI output. This produces structural conflicts of interest: the auditor inherits the same biases and failure modes as the audited.

Clarethium methodology breaks the loop. The substrate uses regex, structural analysis, source comparison, and arithmetic. It runs without invoking AI models on the outputs being measured. AI does not obsolete arithmetic.

This matters because:
- Trust requires verifiability
- Independence is structural, not an aspiration
- Time-locked deterministic measurement compounds where AI-judged measurement does not

---

## Methodology principles

The work rests on four commitments:

1. **Model-independence.** Required measurements operate without AI on the output.
2. **Structural over semantic.** Reproducible structural properties over judgment about meaning.
3. **Calibrated thresholds.** Explicit, versioned, overridable defaults.
4. **Open and verifiable.** Standards are CC-BY; libraries are Apache 2.0; reference test cases are public.

---

## How to engage

- **Read [Lodestone](https://github.com/Clarethium/lodestone)** to adopt the methodology.
- **Read the [Touchstone Standard](https://github.com/Clarethium/touchstone/blob/main/STANDARDS/touchstone-1.0.md)** to understand the measurement substrate.
- **Run [cma](https://github.com/Clarethium/cma)** to adopt compound practice on your local machine.
- **Install [cma-mcp](https://github.com/Clarethium/cma/tree/main/cma-mcp)** (`pip install cma-mcp`) to use the loop in Claude Desktop, Cursor, Cline, or other MCP-compatible AI clients.
- **Install [Frame Check](https://pypi.org/project/frame-check-mcp/)** to add frame analysis to your AI client.
- **Cite the work** when you use it in research, compliance, or applied practice.
- **Propose changes** via the [Touchstone Suggestion Process](https://github.com/Clarethium/touchstone/blob/main/SUGGESTIONS/PROCESS.md) for the Standard, or via issues for individual repositories.
- **Build conforming implementations** in other languages or for specific use cases.

---

## Related

- **[Clarethium website](https://blog.clarethium.com)**: methodology research, blog, mothership.

---

## Status

Lodestone v1.0 published. Touchstone Standard 1.0 drafting in progress; reference implementation feature-complete on `main`. cma 1.0 reference implementation; all seven primitives functional. cma-mcp 0.1 first reference implementation (Python wrapper); installable from source pending PyPI publication. Frame Check operational on PyPI and at frame.clarethium.com.

Watch the [Touchstone repository](https://github.com/Clarethium/touchstone) for the Standard 1.0 release.

---

*The work is open. The substrate is verifiable. The institution stays independent.*
