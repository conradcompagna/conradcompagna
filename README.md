# Conrad Compagna

**PhD historian building AI/ML tools for humanities research.**

[CV](CV.md) · [History & NLP](#history-and-nlp) · [Agentic Search](#agentic-search-and-retrieval) · [Models](#research-models) · [Research & Writing](#research--writing) · [Syllabi](#sample-course-syllabi) · [Classroom Labs](#digital-humanities-classroom-labs) · [Gaming](#gaming) · [Email](mailto:conradcompagna@gmail.com)

My work connects historical research questions with multilingual NLP, structured extraction, knowledge graphs, and interactive software. My research focuses on empire, indigenous agency, and the borderlands linking Burma, China, and northeast India.

## History and NLP

### [Language Engine](https://github.com/conradcompagna/language-engine)

A deployed platform for close reading across modern and historical languages. [Live site](https://language-engine.ai)

- Hybrid browser/server dictionary search, multilingual NLP, and shared INT8 ONNX inference with language adapters.
- Document reading, grammatical overlays, authentication, subscriptions, and usage-budgeted language assistance.

### [Burmese Neural Reader](https://github.com/conradcompagna/burmese-neural-reader)

A deployed reading and linguistic-analysis application for Burmese. [Live reader](https://burmeseneuralreader.com/reader)

- Language-specific segmentation and lexical search combined with spaCy parsing and Stanza entity recognition.
- Corpus preparation, training configurations, evaluation tools, and interactive dependency analysis.

### [Konbaung Chronicle Knowledge Graph](https://github.com/conradcompagna/konbaung-knowledge-graph)

A historical research pipeline and application for examining power in a Burmese royal chronicle. [Research reader](https://burmeseneuralreader.com/chronicles/vol1/47)

- OCR, translation, structured extraction, source alignment, embeddings, and entity-resolution workflows.
- 27,129 canonical claims across 1,215 pages, explored through an RDF-backed reader, graph interface, and documented API.
- **Provisional LLM-as-judge evaluation:** **96.5% semantic precision** and **92.3% inclusive recall** on available annotations across two 5% tranches (122 pages; 2,808 triples). [Evaluation scores](https://github.com/conradcompagna/konbaung-knowledge-graph#extraction-evaluation).
- [Published V3 dataset and embeddings](https://zenodo.org/records/22949204), with source sentences, entity-resolution tables and a [data guide](https://github.com/conradcompagna/konbaung-knowledge-graph/tree/main/research/data-release).

## Agentic Search and Retrieval

### [SearchSpider](https://github.com/conradcompagna/searchspider)

Agentic retrieval for Konbaung historical documents: a deployed research tool that assembles source-linked evidence across Royal Orders and the Burmese royal chronicle. [Live search](https://burmeseneuralreader.com/searchspider/)

- **Search and agent engineering:** local BM25 and CPU ONNX embeddings, document-level hybrid ranking, Gemini query planning, batched evidence assessment and cited synthesis. FastAPI/React deployment with authentication, subscriptions and server-side cost controls.
- **Measured retrieval quality:** **92.6% Hit@10 on 691 targeted English questions** and **96.5% recovery of 2,067 marked question-document pairs across six thematic evidence hunts**. The first 50 results per hunt contain **234/300 reference matches**.
- **Evaluation-driven architecture:** continued reading recovered **173 additional reference matches**, compared with **153** from another query-generation round. Cross-encoder trials informed the final hybrid-ranking design. [Evaluation results and engineering decisions](https://github.com/conradcompagna/searchspider/blob/main/research/README.md).


## Research models

I publish selected trained models on [Hugging Face](https://huggingface.co/conradcompagna),
with model cards, evaluation results and matching downloads in the application repositories.

| Model | What I developed |
|---|---|
| [Arabic clitic tokenizer and expander](https://huggingface.co/conradcompagna/arabic-clitic-tokenizer) | CAMeL teacher supervision over authentic news text, correction rules, transformer tokenization and learned multiword expansion. |
| [Sanskrit sandhi tokenizer and expander](https://huggingface.co/conradcompagna/sanskrit-sandhi-tokenizer) | DCS-based supervision that recovers underlying word forms from sandhied Sanskrit text. |
| [Sanskrit interpretive NER](https://huggingface.co/conradcompagna/sanskrit-interpretive-ner) | An 18-category semantic model trained from Gemini-assisted annotations of authentic Sanskrit documents. |
| [Burmese POS and dependency parser](https://huggingface.co/conradcompagna/burmese-pos-dependency-spacy) | A jointly trained spaCy tok2vec, morphologizer and parser, with reproduced development scores. |

The [Language Engine training record](https://github.com/conradcompagna/language-engine/blob/main/research/models/README.md)
documents all 61 selected custom components and distinguishes them from stock models.

## Research & Writing

My dissertation and three submitted articles examine how imperial power worked through local actors, inherited political practices, and the production of knowledge. The articles below are author manuscripts under review.

### Layered Empire

*Precolonial Continuity, Indigenous Agency, and Hybrid Knowledge on Bengal’s Northeast Frontier, 1790–1810*

PhD dissertation, Birkbeck, University of London.

Examines early colonial rule through the persistence of precolonial political relationships, the agency of indigenous actors, and knowledge produced across languages and communities.

[Read the dissertation (PDF)](research/layered-empire-dissertation.pdf)

### Little Kings, Big Criminals, and Borderlessness on Bengal’s Northern Frontier

Submitted to the *Journal of Borderlands Studies*.

Reconstructs the political landscape behind the Company’s 1792 Welsh expedition, showing how frontier governance responded to mobile military markets, refugees, bandits, and competing local rulers.

[Read the manuscript (PDF)](research/rangpur-borderlands.pdf)

### Empire through the Looking Glass

*Late Eighteenth-Century Colonial Knowledge of Burma*

Submitted to *The Journal of Imperial and Commonwealth History*.

Uses Francis Buchanan’s work on the 1795 Symes embassy to examine how empirical inquiry and diverse local informants produced a multivocal archive within an imperial project.

[Read the manuscript (PDF)](research/empire-through-the-looking-glass.pdf)

### European Subordination and Burmese Realpolitik

*Power Dynamics Across Cultures in the Mid-Eighteenth-Century Irrawaddy Valley*

Submitted to the *Journal of Burma Studies*.

Draws on English, French, and Burmese sources to reconstruct competition among Burmese successor states and European trading companies, examining strategic action across cultural boundaries.

[Read the manuscript (PDF)](research/european-subordination-burmese-realpolitik.pdf)

## Sample Course Syllabi

- [European Imperialism in Asia, 1450–1850 (Online)](syllabi/European_Imperialism_in_Asia_Online.docx)
- [Empire and Nation in Modern China](syllabi/Empire_and_Nation_in_Modern_China.docx)
- [Imperial Thought in Comparative Perspective](syllabi/Imperial_Thought_in_Comparative_Perspective.docx)
- [Natural Language Processing and Large Language Models for Historical Research](syllabi/DH_Syllabus.docx)

## Digital Humanities Classroom Labs

- [Kings and Courts in European Eyes](https://conradcompagna.github.io/courts-in-european-eyes/explorer/)
- [Letters to Networks](https://conradcompagna.github.io/letters-to-networks/explorer/)

## Gaming

Alongside my historical research and NLP platforms, I develop tools for game worlds.

### [Modular Tile Kit Studio](https://github.com/conradcompagna/modular-tile-kit-studio)

A native Godot authoring environment for modular isometric worlds.

- Terrain sculpting, material painting, GPU shaders, GLB processing, and voxel-based spatial validation.
- Canonical board data, undo/redo, image-analysis workflows, and editor regression tests.

## Contact

[conradcompagna@gmail.com](mailto:conradcompagna@gmail.com) · [Full CV](CV.md)
