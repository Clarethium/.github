# Clarethium

Methodology, standards, and reference implementations for AI-coupled work.

Clarethium develops model-independent verification methodology for AI outputs and the tools that implement it. The work is open: standards under CC-BY 4.0, libraries under Apache 2.0.

---

## Projects

### [Touchstone](https://github.com/Clarethium/touchstone)
Model-independent verification for AI-coupled work. The **Touchstone Standard** defines eleven measurement layers for output profiling and five layers for specification compliance verification. The `clarethium-touchstone` library is the reference implementation.

Domain: [touchstone.clarethium.com](https://touchstone.clarethium.com)

### [Frame Check](https://github.com/Clarethium/frame-check-mcp)
Applied tool for frame validation in AI outputs. Uses Clarethium methodology in a specific applied context.

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

Pre-launch for the Touchstone Standard 1.0 (drafting in progress). Frame Check operational. Other projects in development.

Watch the [Touchstone repository](https://github.com/Clarethium/touchstone) for first release.

---

*The work is open. The substrate is verifiable. The institution stays independent.*
