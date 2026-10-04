# Nandhakumar Saravanan

**Research engineer applying AI/ML in life sciences — taking techniques from evaluation through to production.**

I'm a research engineer, and I've spent over three years building AI/ML applications for clinical trials.

The research is the applied kind. I start from a problem, survey what exists or has just been published, test what holds up against real data, and ship what survives. The research and the engineering aren't separate jobs; the second is what the first is for.

Life sciences is where I work, not the limit of what I can work on. I didn't know the domain when I started — I learned its standards and constraints because the problems required it. That's the part that carries.

Outside of work I write, contribute to open source, give talks, enter hackathons and build my own projects.

---

### Things I've built

**[ClinParser](https://github.com/Nandha-kumar-S/clinparser)** · [PyPI](https://pypi.org/project/clinparser/)
Structure-aware PDF parsing for clinical protocols. Parses a protocol into a JSON tree mirroring its own section hierarchy, with each section's text, tables and images attached. Anchors on the section numbering authors maintain for regulatory reasons rather than guessing heading levels from font sizes. No LLM, fully offline — which is what makes it usable on documents carrying PHI.

```bash
pip install clinparser
```

**[SmartClinSAP](https://github.com/Nandha-kumar-S/SmartClinSAP)**
Protocol PDF → CDISC USDM → SADM → Statistical Analysis Plan → executable R and SAS, with statistician review at every stage. Built with a team of four; 1st place in its problem statement at the CDISC AI Innovation Challenge 2026.

**[Protocol Library](https://github.com/Nandha-kumar-S/protocol-library)**
Turns unstructured clinical trial protocols into CDISC USDM, with human-in-the-loop validation. Best Technical Implementation Award, Saama AI CATALYST 2025.

**[mesa-examples#346](https://github.com/mesa/mesa-examples/pull/346)** — merged upstream
Fixed the `color_patches` example, which had silently stopped working under Mesa 3.x: its portrayal returned CanvasGrid-style keys that 3.x ignores, and the README still documented the removed `mesa runserver` flow. A broken example is worse than no example — newcomers copy it and conclude the framework is at fault.

---

### Writing

- [The End of Unstructured Protocol PDFs: AI-Driven Protocol Digitalization](https://medium.com/ai-in-plain-english/the-end-of-unstructured-protocol-pdfs-ai-driven-protocol-digitalization-0daa7ea5134b) — *AI in Plain English*
- [How a 3B Language Model Surpasses an 8B Counterpart with DSPy](https://medium.com/@suriyank532002/how-to-make-small-language-models-outperform-large-language-models-using-dspy-306576d53f2e)
- [Beyond the Hype: Building Agentic Models Without AI](https://medium.com/@suriyank532002/beyond-the-hype-building-agentic-models-without-ai-32f94aeb7152)
- [AI in Life Sciences: Synthetic Dataset Generation Using LLMs](https://medium.com/@suriyank532002/ai-in-life-sciences-enhancing-data-quality-through-synthetic-dataset-generation-using-llms-d819215a3249)

---

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/nandhakumar-s-12a415212/) · [Medium](https://medium.com/@suriyank532002) · [suriyank532002@gmail.com](mailto:suriyank532002@gmail.com)
