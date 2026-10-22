# The Face Value of AI

## When a Selfie Becomes a Prognosis

**The Face Value of AI** is a self-contained interactive scrollytelling essay about facial-health AI, predictive medicine, screening trade-offs, decision value and inference governance.

The project asks a broader Data & AI leadership question:

> As AI becomes able to derive increasingly sensitive conclusions from ordinary data, what must an organization become capable of governing?

The experience is written and designed by **Christopher Hayes, CDAIO, MPS DAV, MBAN, MSc AI, Boston University Candidate**.

## Live experience

### [Open The Face Value of AI interactive experience](https://chrisdhayes.github.io/the-face-value-of-ai/)

Explore the research, test the hypothetical screening scenarios, and examine the governance questions that emerge when AI moves from observation to prediction and action.

> **Educational use only:** This interactive experience is not medical advice, a diagnostic tool, clinical decision-support system or medical device.

## What the experience covers

The story is organized into eight chapters:

1. **From pixels to prediction** — distinguishes structural, physiological, dynamic and prognostic facial signals.
2. **The evidence, carefully read** — compares the meaning and limits of different research metrics.
3. **Breadth does not equal reliability** — examines foundation-model reuse across many biomarker targets.
4. **The value of change** — explores longitudinal facial-age estimates and their limitations.
5. **The false-positive paradox** — provides an interactive screening simulator for prevalence, sensitivity and specificity.
6. **Predicting is not deciding** — illustrates why predictive performance and decision value are different.
7. **The authority to infer** — introduces an original inference-governance framework.
8. **Source notes** — links the empirical claims to primary studies, standards and official guidance.

## Core argument

The project develops four connected propositions:

- **Inference expansion:** the information that can be derived from an existing data asset grows as models improve, even when the source data does not change.
- **The two-clock problem:** model capability can advance faster than evidence, validation, governance and organizational adoption.
- **The decision-value gap:** an accurate prediction does not automatically produce a useful, fair or legitimate decision.
- **Capability versus authority:** what an AI system can infer is not the same as what an organization should authorize it to infer or influence.

These are original conceptual syntheses. They are not presented as empirically validated frameworks or substitutes for clinical, legal, regulatory or professional standards.

## Important limitations

- This project is an educational and editorial artifact.
- It is **not** medical advice.
- It is **not** a diagnostic tool, clinical decision-support system or medical device.
- The 10,000-person screening simulator is hypothetical and is not a result from FAHR-Face or another cited facial-AI system.
- Synthetic charts and conceptual facial overlays are labelled in the experience.
- Survival prediction, diagnostic classification and biomarker correlation answer different scientific questions and should not be interpreted as interchangeable performance measures.

## Repository structure

```text
.
├── index.html   # GitHub Pages entry point; all CSS, SVG and JavaScript are embedded
└── README.md    # Project context, limitations and publishing guidance
```

The project intentionally has no external runtime dependencies, build step or package manager. The full experience is contained in `index.html`.

## Run locally

Opening `index.html` directly in a modern browser should work. For a local web-server test, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Accessibility and interaction

The page includes a skip link, keyboard focus states, semantic section headings, descriptive labels for interactive controls, live-region updates, reduced-motion support, mobile and print layouts, and a no-JavaScript notice.

Accessibility should still be tested with keyboard-only navigation and at least one screen reader before public release.

## Research and citations

Primary research, reporting standards and official Canadian guidance are linked in the final chapter of the experience. The evidence base includes FAHR-Face, FaceAge, MedicalFaceFound, decision-curve analysis, TRIPOD+AI, STARD-AI, Health Canada guidance and guidance from the Office of the Privacy Commissioner of Canada.

The repository reports and interprets published material. It does not independently validate the cited models or determine whether any system is suitable for clinical deployment.

## AI-use disclosure

AI was used as a research, analytical and editorial partner to organize the evidence base, test the thesis, identify counterarguments and potential overclaims, check illustrative calculations, and refine the writing and visual frameworks.

Christopher Hayes reviewed the underlying sources and made the final decisions about the argument, interpretation, evidence, structure, language, frameworks and conclusions.

## Suggested citation

Hayes, C. (2026). *The Face Value of AI: When a Selfie Becomes a Prognosis*. Interactive research and editorial project.

## License and reuse

No open-source license is included in this repository. Unless a license is added, the project remains under the author's copyright and reuse is not automatically granted.

Third-party studies and linked materials remain subject to their respective publishers' and authors' rights.
