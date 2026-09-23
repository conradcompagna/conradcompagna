# Conrad Compagna

[Profile](README.md) · [Download CV (PDF)](CV.pdf) · [conradcompagna@gmail.com](mailto:conradcompagna@gmail.com)

Nanaimo, British Columbia, Canada

Computational and Digital Humanities | Historian of Empire and Asian Borderlands

I am a PhD historian and digital humanities specialist with a content focus on imperial history and the borderlands linking Burma, China and northeast India. I combine source-language scholarship with full-stack software engineering, applied LLM engineering, NLP model training and statistical, network and spatial analysis. My work includes three completed journal manuscripts, all submitted, a fourth computational-history article in preparation, a source-linked knowledge graph built from the Konbaung chronicles, and two shipped NLP reading platforms of which I am the sole founder and developer. I bring approximately seven years of classroom experience and original course design across global, imperial and Asian history, alongside computational approaches to the humanities.

## Education

PhD, History | Birkbeck, University of London | 2020–2026

Dissertation: [Layered Empire: Precolonial Continuity, Indigenous Agency, and Hybrid Knowledge on Bengal's Northeast Frontier, 1790–1810](research/layered-empire-dissertation.pdf).

MSc, History | University of Edinburgh | 2018–2020

BA (Honours), History | University of British Columbia | 2008–2012

## Research and manuscripts

- [European Subordination and Burmese Realpolitik: Power Dynamics Across Cultures in the Mid-Eighteenth-Century Irrawaddy Valley](research/european-subordination-burmese-realpolitik.pdf) — Journal of Burma Studies, under review.

- [Little Kings, Big Criminals, and Borderlessness on Bengal’s Northern Frontier](research/rangpur-borderlands.pdf) — Journal of Borderlands Studies, under review.

- [Empire through the Looking Glass: Late Eighteenth-Century Colonial Knowledge of Burma](research/empire-through-the-looking-glass.pdf) — Journal of Imperial and Commonwealth History, under review.

- “The Power of Naming: Tracing Offices, Titles and Patronage in the Konbaung Dynasty through Knowledge Graphs” — in preparation. Combines corpus statistics, network and linguistic analysis, and case studies derived from close reading to examine how the Burmese crown centralized the authority to name and delegate in a setting where it could not establish a monopoly of coercive force.

### Computational Approaches to Comparative Empire

Planned monograph extending computational methods to the mountainous highlands between China, Burma and India. Uses large-scale multilingual information extraction and corpus analytics to examine the extent to which European and non-European imperial powers converged on similar methods in their governance and representation of mobile and decentralized highland populations.

## Digital humanities projects

### Founder and Developer | language-engine.ai | 2025–present

[Source code](https://github.com/conradcompagna/language-engine)

- Built and shipped a full-stack multilingual NLP reading platform covering more than thirty modern and historical languages, including Japanese, Chinese, Classical Chinese, Korean, Sanskrit, Latin, Greek and Old English.

- Custom-trained transformer models provide tokenization, sentence segmentation, part-of-speech tagging, morphological analysis, lemmatization, dependency parsing and named-entity recognition tailored to each language.

- Created training datasets through synthetic-data generation and human-in-the-loop curation; carried models through training, evaluation and application integration.

- Rewrote the Python model harness to bake dozens of language-specific adapters into static graphs, enabling quantization and CPU deployment of a large research model on a commercial web server.

- Constructed a multi-gigabyte SQLite lexicon from dozens of digitized dictionaries; implemented a prefix- and suffix-aware dynamic-programming word-matching algorithm and language-specific matching rules.

- Integrated the Gemini API for per-token glossing, sentence translation and contextual analysis, including conversation history storage and reinjection, gloss validation and retries, and token usage monitoring.

- Built script-aware transliteration for non-Latin languages and PDF, Word, e-book and HTML rendering, including custom web-capture tooling.

- Owned end-to-end product delivery: user accounts, Stripe billing, analytics, Flask services and deployment using Linux, Gunicorn and Nginx.

### Founder and Developer | burmeseneuralreader.com | 2024–present

[Source code](https://github.com/conradcompagna/burmese-neural-reader)

- Built and shipped a Burmese reading platform using unigram- and bigram-based statistical language modeling for dictionary segmentation of continuous text without word spaces.

- Trained spaCy models on experimental research datasets for part-of-speech tagging, named-entity recognition and dependency parsing; integrated these analyses into the reading interface through pop-ups and visualization.

- Developed extensive logic for normalizing and reconstructing OCR-damaged historical text, including fuzzy dictionary lookup with BK-trees and Levenshtein edit distance.

- Assembled a large online digitized Burmese lexicon, including Burmese–Pali dictionaries for historical and religious texts.

### Developer and Researcher | Konbaung Chronicles Project | 2026–present

[Source code](https://github.com/conradcompagna/konbaung-knowledge-graph)

- Built a domain-specific, LLM-powered document extraction pipeline, digitizing, translating and extracting 27,000 triples from a large historical corpus written in eighteenth-century Burmese.

- Designed an ontology of 52 entity categories and 81 relation categories for a knowledge graph stored in Oxigraph and queried through SPARQL and a Flask backend.

- Engineered domain-specific LLM prompts, structured outputs and layered extraction passes across tens of millions of annotation tokens; retained sentence/page provenance so extracted relations remain inspectable against the source.

- Used Gemini vector embeddings for semantic search, entity-resolution candidate discovery and semantic-community clustering.

- Built a Graphology/Sigma browser interface for page, range, focused, thematic, volume and corpus-level network exploration, with relations linked to their supporting evidence and data accessible through an API.

- Applied statistical, network and linguistic analysis to the database for an article in preparation on titles, offices and patronage in the dynasty, connecting the engineered database to original research.

## Teaching experience

### Beijing No. 101 High School | Beijing | 2017–2022

- Empire in Asia: From the Mongols to Decolonization; Comparative Politics; and European History: Late Middle Ages to the Present.

### Beijing No. 8 High School | Beijing | 2023–2024

- Art History: Prehistory to 1500 CE.

### New Oriental Foreign Language School | Yangzhou | 2016–2017

- The Americas in Global Perspective.

## Editorial experience

### Columnist and Editor | China Daily | 2022–2023

- Wrote monthly history-themed columns; edited and ghostwrote news copy; conducted background research, fact-checking and Mandarin/English translation.

## Content specialisms

Global and imperial history; South, Southeast and East Asia since 1500; the East India Company; comparative empire; borderlands; indigenous agency; colonial knowledge; digital humanities; natural language processing; computational linguistics.

## Technical expertise

NLP: Hugging Face Transformers; PyTorch; TensorFlow; CUDA; transformer and BiLSTM architectures; corpus construction; synthetic datasets; model training and evaluation; runtime quantization; tokenization; morphological analysis; dependency parsing; named-entity recognition; vector embeddings; semantic search.

Software and data: Python; JavaScript; Node.js; HTML/CSS; Flask; SQLAlchemy; SQLite; REST APIs; Linux; Gunicorn; Nginx; dynamic programming; knowledge graphs; RDF; SPARQL; Oxigraph; corpus analysis; data visualization.

Applied LLM engineering: Codex; Claude Code; CLI environments; prompt engineering; context-window management; multi-agent orchestration; Git management; review and QA; LLM API integration; structured outputs.

## Languages

Mandarin Chinese: full speaking and reading ability. Burmese and French: reading.

## References

References available on request.
