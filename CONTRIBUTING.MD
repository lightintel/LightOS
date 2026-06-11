Contributing to Light OS

Welcome. You found this repository because something in the manifesto resonated — a frustration with computing as it is, or a curiosity about computing as it could be. Either is a good reason to be here.

Light OS is an independent project in early development. Contributions at every level are meaningful: from fixing a typo in the manifesto to proposing a data model for the LightFileSystem. This document explains how to contribute effectively.


What we need most right now

Light OS is at the stage where architecture and thinking matter more than code. The most valuable contributions today are:

Research and specification work
The open problems in README.md are real, unsolved, and consequential. If you have expertise in distributed systems, quantum networking, operating system design, or natural language processing, your thinking on these problems is more valuable right now than any code.

Language corpus contributions
The multilingual kernel requires linguistic knowledge for every Bharatiya language and eventually every world language. If you are a native speaker of any language — particularly languages underserved by existing NLP infrastructure — your knowledge of vocabulary, grammar, dialect, and idiomatic expression is as essential as any engineer's code.

Architecture review
The specifications in architecture/ are drafts. They need review from people who know distributed systems, kernel engineering, networking protocols, and programming language theory. Critique is a contribution. A well-reasoned objection is more valuable than agreement.

ErlOS kernel development
The Erlang/BEAM-based kernel prototype needs engineers comfortable with Erlang, x86 assembly, C, and low-level systems programming. See kernel/erlos/ for current state and open issues.


How to contribute

For ideas, questions, and architecture discussion

Open a GitHub Discussion. Use the appropriate category:


Architecture — proposals, critiques, and questions about the six core systems
Hard Problems — engagement with the four open research questions
Languages — contributions and questions about the multilingual kernel
General — everything else


Discussions are the primary venue for thinking together before writing code or specifications.

For specification contributions

The files in architecture/ are living documents. To contribute:


Fork the repository
Create a branch: git checkout -b architecture/chakravyuh-cap-theorem-response
Edit the relevant .md file in architecture/
Open a pull request with a clear description of what you added and why


Specification PRs should include: the claim being made, the reasoning behind it, and at minimum one counter-argument you have considered and addressed.

For code contributions (ErlOS)


Fork the repository
Create a branch: git checkout -b kernel/protected-mode-gdt-fix
Make your changes with clear commit messages
Ensure your code compiles and boots in QEMU before submitting
Open a pull request referencing any related issue or discussion


For significant changes — new subsystems, architectural decisions — open a Discussion first. Code that arrives without prior discussion is harder to review well.

For translations of the manifesto

The manifesto may be translated into any language. To contribute a translation:


Create a file: MANIFESTO.{language-code}.md (e.g. MANIFESTO.ta.md for Tamil, MANIFESTO.hi.md for Hindi)
Translate faithfully — preserve the structure and intent, not just the words
Add your name as translator at the bottom of the file
Open a pull request


Every language deserves to read the manifesto in its own tongue. Translation contributions are among the most meaningful this project can receive.


Standards for contributions

Be specific. Vague enthusiasm is welcome in discussions but not in pull requests. A PR description that says "improved the architecture" without saying how will be returned for revision.

Be honest about uncertainty. If you are proposing something you are not certain of, say so. Light OS is working on hard problems. Intellectual honesty about what is solved and what is not is a core value of this project.

Engage with the hard problems, not around them. The CAP theorem, the QKD hardware dependency, the cold-start language problem — these are real constraints. Contributions that acknowledge and address them are more valuable than contributions that ignore them.

Preserve the civilisational framing. The Bharatiya intellectual heritage in Light OS — the Chakravyuh, the heliocentric framework, the Vedantic architectural concepts — is not decoration. It is the structural intellectual foundation of the project. Contributions should engage with this framing, not flatten it into generic Western computing vocabulary.


Code of conduct

This project is built on the conviction that every human being — regardless of their language, their geography, their institution, or their resources — deserves computing built for them. That conviction applies to how we treat each other.

Engage with ideas rigorously. Engage with people respectfully. Disagreement is welcome; contempt is not.


What you are joining

In 1991, Linus Torvalds posted: "I'm doing a (free) operating system (just a hobby, won't be big and professional like gnu) for 386(486) AT clones."

Linux now runs most of the world's servers.

Light OS begins with a larger vision and a more explicit declaration of intent. Whether it reaches the scale of that vision depends entirely on whether the people who read the manifesto decide to build it.

You are one of those people.

The notebook is where it started.
The repository is where it becomes code.
The code is where it becomes the world.


Contact

Kathir (Kathira)
Independent Researcher, Policy Analyst, and Inventor
Coimbatore, Tamil Nadu, Bharat

Open an issue or discussion for project-related contact. For patent and licensing inquiries, reference the provisional applications filed with the Indian Patent Office.


All contributions to this repository are made under the terms described in LICENSE. By submitting a pull request, you agree that your contribution may be distributed under those terms.
