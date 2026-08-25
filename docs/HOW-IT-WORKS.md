# How Sketch Works

The visuals on this page are static SVGs, so they render directly on GitHub on phones and desktop browsers. Each one is generated from a model specific to this skill.

## System architecture

![Detailed system map for Sketch](../assets/system-map.svg)

### Components

- **1. Product question:** participates in define the single design decision to explore.
- **2. Shared content model:** participates in create common content and constraints.
- **3. Variant A:** participates in build two or three html variants.
- **4. Variant B:** participates in render at desktop and phone sizes.
- **5. Comparison notes:** participates in compare hierarchy density and interaction.

## Actor and data sequence

![Actor and data sequence for Sketch](../assets/operation-sequence.svg)

### 1. Define the single design decision to explore

**Primary surface:** `Product question`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 2. Create common content and constraints

**Primary surface:** `Shared content model`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 3. Build two or three HTML variants

**Primary surface:** `Variant A`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 4. Render at desktop and phone sizes

**Primary surface:** `Variant B`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 5. Compare hierarchy density and interaction

**Primary surface:** `Comparison notes`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 6. Keep the selected direction or discard all

**Primary surface:** `Product question`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.

## Example output shape

![Illustrative output for Sketch](../assets/example-output.svg)

The example is a visual contract: a real run may look different, but it should expose comparable state, provenance, and verification information. It is not presented as evidence of a live external action.

## Decision and stop conditions

![Decision guide for Sketch](../assets/decision-guide.svg)

The workflow stops when the target is ambiguous, the relevant surface is unavailable or unauthorized, or the final artifact cannot be checked. A logged-in session or successful tool call is not by itself proof that the requested outcome is complete.

## Verification checklist

- Confirm every component shown in the system map exists in the target environment.
- Trace the actor sequence using actual tool output or artifact state.
- Compare the result with the example-output information contract.
- Re-read or reopen the final artifact instead of trusting an attempt message.
- Report omitted stages, unsupported capabilities, and remaining human decisions.
