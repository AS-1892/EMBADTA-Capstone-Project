Reflexive AI

Context-Preserving AI for Qualitative Research

Reflexive AI is a research prototype that explores how artificial intelligence can be integrated into qualitative analysis without eroding context, evidence, or researcher accountability. The project responds to a growing tension in AI-assisted research: while large language models can rapidly generate themes and summaries, they often obscure how those insights were produced, whose voices they represent, and where human judgment intervened.

This system is built on a simple but non-negotiable premise:
AI should assist qualitative analysis, not silently replace methodological rigor.

What Problem Does Reflexive AI Address?

Most AI tools for qualitative research optimize for speed and abstraction. In doing so, they tend to:

Detach themes from original participant quotes

Flatten demographic and contextual differences

Hide researcher decisions behind seemingly authoritative outputs

Make bias and representation issues difficult to detect after the fact

Reflexive AI was designed to counter these tendencies by structurally enforcing reflexivity, traceability, and transparency throughout the analytic workflow.

Core Design Principles

Reflexive AI operationalizes qualitative best practices through software constraints rather than relying on user intention alone:

Quote-Level Traceability
Every code and theme is explicitly linked back to original participant statements and IDs.

Human-in-the-Loop Control
AI may suggest codes and themes, but all analytic decisions require researcher confirmation, revision, or rejection.

Context Preservation
Participant metadata (e.g., gender, tech comfort, session timing) is preserved and surfaced during interpretation rather than stripped away during analysis.

Bias & Representation Awareness
The system actively checks for missing voices, demographic imbalance, and contradiction signals instead of assuming neutrality.

Reflexivity as a First-Class Artifact
Researchers are required to document assumptions, uncertainties, and interpretive decisions through structured reflexive notes.

How the System Works (High Level)

The workflow follows a disciplined, staged qualitative process:

Study Setup & Data Context
Establishes participant context and data quality signals before any analysis occurs.

AI Familiarisation
A read-only AI pass that mirrors human familiarisation without generating analytic outputs.

Open Coding (AI-Assisted, Researcher-Controlled)
AI suggests codes grounded in individual quotes; researchers review and finalize each code.

Theme Construction
Themes may be AI-suggested or manually constructed, but interpretive authority always remains human.

Reflexive Audit Mode
Once themes are finalized, analysis is locked and the system shifts to evaluation—surfacing representation gaps, AI influence, and internal tensions.

Researcher Reflexive Notes
The researcher records interpretive decisions, assumptions, and unresolved questions as part of the analytic record.

Throughout this process, an audit sidebar tracks AI actions, researcher decisions, and reflexive engagement—making analytic labor visible rather than implicit.

What This Project Is (and Is Not)

Reflexive AI is:

A design-science research artifact

A methodological intervention for responsible AI use

A proof of concept for context-preserving qualitative analysis

Reflexive AI is not:

An attempt to automate qualitative judgment

A replacement for trained researchers

A production-ready analytics platform

Technology Stack

Python

Streamlit (interactive research interface)

OpenAI API (LLM-based assistance)

Pandas (data and metadata handling)

Research Context

This project was developed as part of an Executive MBA (Digital Transformation & Analytics) capstone, grounded in literature on:

Human-centred AI

Computational grounded theory

Algorithmic bias

Qualitative research rigor

While demonstrated using synthetic data, the system is designed to generalize to real-world qualitative research settings.

Why Reflexive AI Matters

As AI tools become embedded in research and decision-making workflows, how insights are produced matters as much as the insights themselves. Reflexive AI demonstrates one possible path forward—where AI augments human sense-making without dissolving accountability, context, or interpretive depth.
