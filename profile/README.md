# Clarethium

The canonical methodology for AI-coupled work.

Clarethium publishes reference artifacts and tooling for measuring AI outputs, orienting operator practice, and sharpening craft. The work is open: reference texts under CC-BY 4.0, libraries under Apache 2.0.

---

## Projects

**Open methodology reference artifacts:**

### [Touchstone](https://github.com/Clarethium/touchstone)
Validates work against quality standards. The **Touchstone Standard** defines eleven measurement layers for AI output profiling: structural composition, claim density, source matching, grounding decomposition, and others. The `clarethium-touchstone` library is the reference Python implementation.

Domain: [touchstone.clarethium.com](https://touchstone.clarethium.com)

### [Lodestone](https://github.com/Clarethium/lodestone)
Orients practice. The canonical operator methodology for working with AI systems: stance, loop, calibration, altitude, failure shapes, quality levels, surface protocols, compound practice. Reference manuscript under CC-BY 4.0.

**Companion tooling:**

### [cma](https://github.com/Clarethium/cma)
Executable compound-practice loop. The terminal-side companion to Lodestone: captures failures, surfaces relevant context at the moment of action, tracks decisions, detects recurrence patterns.

**Applied vehicles:**

### [Frame Check](https://github.com/Clarethium/frame-check-mcp)
Applied tool for frame validation in AI outputs. Built on the Touchstone substrate.

Domain: [frame.clarethium.com](https://frame.clarethium.com)

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

- **Read the [Touchstone Standard](https://github.com/Clarethium/touchstone/blob/main/STANDARDS/touchstone-1.0.md)** if you want to understand the methodology.
- **Use the libraries** to verify AI outputs in your work.
- **Cite the Standard** when you use the methodology in research or compliance.
- **Propose changes** via the [Suggestion Process](https://github.com/Clarethium/touchstone/blob/main/SUGGESTIONS/PROCESS.md).
- **Build conforming implementations** in other languages or for specific use cases.

---

## Related

- **Clarethium website** ([blog.clarethium.com](https://blog.clarethium.com)) - methodology research, blog, mothership.

---

## Status

Touchstone Standard 1.0 in late draft (Sections 2 and 11 require operator authoring before ratification). Lodestone v1.0 manuscript drafted across nine sections. cma 1.0 reference implementation operational. Frame Check operational.

Watch the [Touchstone repository](https://github.com/Clarethium/touchstone) for first ratified release.

---

*The work is open. The substrate is verifiable. The institution stays independent.*
