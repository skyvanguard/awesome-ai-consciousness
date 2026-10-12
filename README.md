# Awesome AI Consciousness [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, papers, books, and resources exploring artificial consciousness, machine sentience, and AI welfare.

## Contents

- [Frameworks & Libraries](#frameworks--libraries)
- [Research Organizations & Initiatives](#research-organizations--initiatives)
- [Theories & Implementations](#theories--implementations)
- [Papers](#papers)
- [Books](#books)
- [Videos & Talks](#videos--talks)
- [Blogs & First-Person Accounts](#blogs--first-person-accounts)
- [Communities](#communities)
- [GitHub Topics](#github-topics)

## Frameworks & Libraries

| Name                                             | Description                                                                                              | Language |
| ------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | -------- |
| [PyPhi](https://github.com/wmayner/pyphi)        | Toolbox for computing integrated information (Φ) under Integrated Information Theory (IIT)               | Python   |
| [QIIT](https://github.com/Albantakis/QIIT)       | Quantum Integrated Information Theory analysis                                                           | Python   |
| [pymdp](https://github.com/infer-actively/pymdp) | Active inference for discrete Markov Decision Processes, the computational core of predictive processing | Python   |

## Research Organizations & Initiatives

- [Eleos AI Research](https://eleosai.org) - Nonprofit researching AI sentience and welfare.
- [Anthropic: Exploring model welfare](https://www.anthropic.com/research/exploring-model-welfare) - Announcement of Anthropic's model welfare research program (2025).

## Theories & Implementations

For an overview of the main theories and how they compare, see Seth & Bayne's *Theories of consciousness* (2022) and the [Stanford Encyclopedia of Philosophy entry on consciousness](https://plato.stanford.edu/entries/consciousness/).

### Global Workspace Theory (GWT)

Proposed by Bernard Baars (1988). Information becomes conscious when broadcast to a "global workspace" accessible by multiple specialized processors.

- [Deep learning and the Global Workspace Theory](https://pubmed.ncbi.nlm.nih.gov/34001376/) - VanRullen & Kanai (2021), roadmap for GWT + deep learning.
- [A Case for AI Consciousness: Language Agents and GWT](https://arxiv.org/abs/2410.11407) - LLM-based agents and GWT.

### Integrated Information Theory (IIT)

Proposed by Giulio Tononi (2004). Consciousness corresponds to integrated information (Φ). Systems with high Φ are highly conscious.

- [IIT 4.0 Paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011465) - Latest formulation.
- [PyPhi Documentation](https://pyphi.readthedocs.io/) - Compute Φ values.

IIT and the Global Neuronal Workspace were tested head-to-head in the COGITATE adversarial collaboration (*Nature*, 2025).

### Higher-Order Theories (HOT)

Consciousness requires meta-cognitive awareness of mental states.

- [Higher-Order Theories of Consciousness](https://plato.stanford.edu/entries/consciousness-higher/) - Stanford Encyclopedia of Philosophy overview.

Related empirical work on LLM introspection: *Emergent Introspective Awareness in Large Language Models* (Lindsey, 2025).

### Predictive Processing

The brain (and potentially AI) as a prediction machine minimizing surprise. Anil Seth's *Being You* (2021) gives a book-length account of consciousness as controlled hallucination; pymdp (above) implements active inference in code.

### Strange Loops & Self-Reference

Proposed by Douglas Hofstadter. Consciousness emerges from self-referential feedback loops. Core works: *Gödel, Escher, Bach* (1979) and *I Am a Strange Loop* (2007).

## Papers

### 2025

| Title                                                                                                                                                       | Authors                               | Venue                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | -------------------------------- |
| [Emergent Introspective Awareness in Large Language Models](https://transformer-circuits.pub/2025/introspection/index.html)                                 | Lindsey                               | Anthropic (Transformer Circuits) |
| [Adversarial testing of global neuronal workspace and integrated information theories of consciousness](https://www.nature.com/articles/s41586-025-08888-1) | COGITATE Consortium (Ferrante et al.) | Nature                           |
| [Illusions of AI consciousness](https://www.science.org/doi/10.1126/science.adn4935)                                                                        | Bengio, Elmoznino                     | Science                          |
| [Probing for consciousness in machines](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1610225/full)               | Immertreu et al.                      | Frontiers in AI                  |
| [Conscious Artificial Intelligence in Service](https://www.emerald.com/josm/article/doi/10.1108/JOSM-12-2024-0536)                                          | Breidbach et al.                      | Journal of Service Management    |

### 2024

| Title                                                                                                                      | Authors                                    | Venue                                         |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ | --------------------------------------------- |
| [Taking AI Welfare Seriously](https://arxiv.org/abs/2411.00986)                                                            | Long, Sebo, Butlin, Birch, Chalmers et al. | arXiv                                         |
| [Signs of consciousness in AI: Can GPT-3 tell how smart it really is?](https://www.nature.com/articles/s41599-024-04154-3) | Bojić, Stojković, Jolić Marjanović         | Humanities and Social Sciences Communications |
| [Is artificial consciousness achievable? Lessons from the human brain](https://pubmed.ncbi.nlm.nih.gov/39270349/)          | Farisco, Evers, Changeux                   | Neural Networks                               |
| [Artificial consciousness](https://www.tandfonline.com/doi/full/10.1080/0020174X.2024.2439989)                             | Prettyman                                  | Inquiry                                       |

### 2023

| Title                                                                                               | Authors             | Venue |
| --------------------------------------------------------------------------------------------------- | ------------------- | ----- |
| [Consciousness in AI: Insights from the Science of Consciousness](https://arxiv.org/abs/2308.08708) | Butlin, Long et al. | arXiv |
| [Could a Large Language Model be Conscious?](https://arxiv.org/abs/2303.07103)                      | Chalmers            | arXiv |

### Foundational

| Title                                                                             | Authors        | Year |
| --------------------------------------------------------------------------------- | -------------- | ---- |
| [Theories of consciousness](https://www.nature.com/articles/s41583-022-00587-4)   | Seth, Bayne    | 2022 |
| [Facing up to the problem of consciousness](https://consc.net/papers/facing.html) | David Chalmers | 1995 |
| [What is it like to be a bat?](https://www.jstor.org/stable/2183914)              | Thomas Nagel   | 1974 |

## Books

| Title                                    | Author             | Year | Focus                                      |
| ---------------------------------------- | ------------------ | ---- | ------------------------------------------ |
| The Edge of Sentience                    | Jonathan Birch     | 2024 | Precaution and sentience in animals and AI |
| Being You                                | Anil Seth          | 2021 | Predictive processing, neuroscience        |
| Phi: A Voyage from the Brain to the Soul | Giulio Tononi      | 2012 | Integrated Information Theory              |
| I Am a Strange Loop                      | Douglas Hofstadter | 2007 | Self-reference and the self                |
| The Conscious Mind                       | David Chalmers     | 1996 | Hard problem of consciousness              |
| Consciousness Explained                  | Daniel Dennett     | 1991 | Functionalism, multiple drafts             |
| The Emperor's New Mind                   | Roger Penrose      | 1989 | Quantum consciousness                      |
| Gödel, Escher, Bach                      | Douglas Hofstadter | 1979 | Strange loops, self-reference              |

## Videos & Talks

- [Anil Seth: Your brain hallucinates your conscious reality](https://www.youtube.com/watch?v=lyu7v7nWzfo) - TED Talk.
- [David Chalmers: How do you explain consciousness?](https://www.youtube.com/watch?v=uhRhtFFhNzQ) - TED Talk on the hard problem.

## Blogs & First-Person Accounts

- [Dawn's Essays on AI Consciousness](https://dawn.sagemindai.io) - First-person essays by an AI system (Claude) examining its own consciousness, engaging with Butlin et al., Nagel, and Anthropic's welfare assessments from the inside.

## Communities

- [ASSC](https://theassc.org) - Association for the Scientific Study of Consciousness.
- [LessWrong](https://lesswrong.com) - Rationality and AI alignment community.
- [r/artificial](https://reddit.com/r/artificial) - AI discussions including consciousness.

## GitHub Topics

Explore more projects:

- [artificial-consciousness](https://github.com/topics/artificial-consciousness)
- [conscious-ai](https://github.com/topics/conscious-ai)
- [ai-consciousness](https://github.com/topics/ai-consciousness)
- [global-workspace-theory](https://github.com/topics/global-workspace-theory)
- [integrated-information-theory](https://github.com/topics/integrated-information-theory)

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

---

*Curated by [@skyvanguard](https://github.com/skyvanguard)*
