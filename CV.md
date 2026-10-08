# Conrad Compagna

[Download CV (PDF)](CV.pdf)

**Historian of Empire and Asian Borderlands | NLP and LLM Engineering | Research Software Development**

Nanaimo, British Columbia, Canada · [conradcompagna@gmail.com](mailto:conradcompagna@gmail.com) · +1 (250) 619-0788

[github.com/conradcompagna](https://github.com/conradcompagna) · [language-engine.ai](https://language-engine.ai) · [burmeseneuralreader.com](https://burmeseneuralreader.com)

My research focuses on empire and the borderlands linking Burma, China and northeast India, particularly indigenous agency, political authority and colonial knowledge. I have increasingly turned to natural language processing and LLM engineering as tools to support historical research and to answer questions through large-scale analysis of texts. My work includes two neural-network-powered reading platforms covering many low-resource and historical languages; the digitization, machine translation and construction of a knowledge graph from the collected chronicles of Burma’s last historical dynasty; and an agentic retrieval system using vector embeddings and keyword searches orchestrated by an LLM agent over an 11-volume corpus of Burmese historical material. I look forward to further exploring how both classical NLP and transformer-based neural networks can contribute to solving complex problems in the humanities and social sciences.

## Education

**PhD, History | Birkbeck, University of London | 2020–2026**

Dissertation: [Layered Empire: Precolonial Continuity, Indigenous Agency, and Hybrid Knowledge on Bengal’s Northeast Frontier, 1790–1810](https://github.com/conradcompagna/conradcompagna/blob/main/research/layered-empire-dissertation.pdf).

**MSc, History | University of Edinburgh | 2018–2020**

**BA (Honours), History | University of British Columbia | 2008–2012**

## Historical research and manuscripts

- [European Subordination and Burmese Realpolitik: Power Dynamics Across Cultures in the Mid-Eighteenth-Century Irrawaddy Valley](https://github.com/conradcompagna/conradcompagna/blob/main/research/european-subordination-burmese-realpolitik.pdf) — Journal of Burma Studies, under review.

- [Little Kings, Big Criminals, and Borderlessness on Bengal’s Northern Frontier](https://github.com/conradcompagna/conradcompagna/blob/main/research/rangpur-borderlands.pdf) — Journal of Borderlands Studies, under review.

- [Empire through the Looking Glass: Late Eighteenth-Century Colonial Knowledge of Burma](https://github.com/conradcompagna/conradcompagna/blob/main/research/empire-through-the-looking-glass.pdf) — Journal of Imperial and Commonwealth History, under review.

- “An Impossibly King-Centred Universe: Mapping Power and Ideology in the Konbaungset Yazawin through Knowledge Graphs” — in preparation. Uses a large-scale graph database of the chronicle’s claims about power to ask what political world emerges when those claims are examined together.

- Computational Approaches to Comparative Empire — planned monograph. Uses large-scale LLM tagging and corpus analysis to extract and compare references to highland peoples from the records of European and non-European lowland empires that governed the Southeast Asian massif over centuries. Asks what patterns in imperial representations and practices become visible when these references are brought together across languages, empires and periods.

## Computational research and software

### Language Engine

*Founder and Developer | 2025–present*

[Live platform](https://language-engine.ai) · [Code and model documentation](https://github.com/conradcompagna/language-engine)

- Built a multilingual reading platform to bring document reading, dictionary lookup and grammatical analysis together for 27 modern and historical languages, including everything from Thai, Japanese and Korean to Latin, Ancient Greek, Sanskrit and Classical Chinese.

- Produced and prepared datasets and trained and evaluated neural models to identify word boundaries, lemmas, inflections, and grammatical structure across all supported languages, totaling 61 custom-trained components alongside significant experimentation.

- Quantized the models and rewrote their inference code to run on a CPU.

- Integrated a large bank of dictionaries into an SQLite database served by a compact, browser-side word-matching algorithm operating over extensive, language-specific normalization rules.

- Connected the site to the Gemini API for translation and glossing through structured JSON outputs; wrote a chatbot harness managing context for sustained interaction with Gemini through the site interface.

- Wrote script-aware transliteration modules for all non-Latin languages.

- Implemented geometry-preserving, interactive document display for PDFs, Word documents, HTML and multiple e-book formats.

- End-to-end product delivery included user accounts, Stripe billing, analytics, Flask services and deployment using Linux, Gunicorn and Nginx.

### Burmese Neural Reader

*Founder and Developer | 2024–present*

[Live platform](https://burmeseneuralreader.com) · [Code and released parser](https://github.com/conradcompagna/burmese-neural-reader)

- Built a reader for historical Burmese, where text without whitespace and OCR errors complicate word recognition. Segmentation used a statistical language model, which outperformed neural networks trained on modern text.

- Trained a custom spaCy model suite to identify parts of speech, grammatical forms and relationships between words using experimental research data.

- Used a Levenshtein edit-distance algorithm to perform fuzzy matching on OCR-damaged text inputs with archaic spellings.

- Neural analysis pairs with multiple stacked Burmese and Burmese–Pali dictionaries in the live reader, allowing users to visually see and inspect word meanings, sentence structure and pronunciation on any input text.

### Konbaung Chronicle Knowledge Graph

*Developer and Researcher | 2026–present*

[Live explorer](https://burmeseneuralreader.com/knowledge-graph/vol1/47) · [Code](https://github.com/conradcompagna/konbaung-knowledge-graph) · [Dataset](https://zenodo.org/records/22949204)

- Used large language models to extract 27,129 historical claims bearing on power relations from three volumes of Burmese historical prose. Each claim is stored in an RDF triples database linked back to its underlying source; entities and relations were then grouped into a closed-class set of axial categories in a second pass; a third disambiguation pass reduced the set of nearly 20,000 entities clustered together using vector embeddings.

- Deployed a searchable database and an interactive graph explorer showing people, places, offices and their relationships, and released the underlying dataset on Zenodo.

- Analysed the resulting corpus, combining large-scale statistical, network and linguistic analysis with close reading.

### SearchSpider

*Developer and Researcher*

[Live historical search](https://burmeseneuralreader.com/searchspider/) · [Code and evaluation](https://github.com/conradcompagna/searchspider)

- Built and deployed a research system to find and assess evidence across Burmese royal orders and chronicles.

- Keyword and vector searches using a quantized embedding model are orchestrated by an LLM agent that plans searches, assesses retrieved evidence and produces grounded, source-linked provisional answers to research questions while summarizing and tagging hundreds of primary documents that may be of value across a multivolume dataset comprising the majority of historical material on the dynasty by page volume.

## Teaching and editorial experience

### History and politics teaching

- Beijing No. 101 High School | 2017–2022: Empire in Asia: From the Mongols to Decolonization; Comparative Politics; European History: Late Middle Ages to the Present.

- Beijing No. 8 High School | 2023–2024: Art History: Prehistory to 1500 CE.

- New Oriental Foreign Language School, Yangzhou | 2016–2017: US History.

### Columnist and Editor | China Daily | 2022–2023

- Wrote history-themed columns; edited and ghostwrote news; conducted research, fact-checking and Mandarin-to-English translation.

### Prepared course syllabi

- [European Imperialism in Asia, 1450–1850 (Online)](https://github.com/conradcompagna/conradcompagna/blob/main/syllabi/European_Imperialism_in_Asia_Online.docx)

- [Empire and Nation in Modern China](https://github.com/conradcompagna/conradcompagna/blob/main/syllabi/Empire_and_Nation_in_Modern_China.docx)

- [Imperial Thought in Comparative Perspective](https://github.com/conradcompagna/conradcompagna/blob/main/syllabi/Imperial_Thought_in_Comparative_Perspective.docx)

- [Natural Language Processing and Large Language Models for Historical Research](https://github.com/conradcompagna/conradcompagna/blob/main/syllabi/DH_Syllabus.docx)

### Digital humanities teaching materials

- [Kings and Courts in European Eyes](https://github.com/conradcompagna/courts-in-european-eyes): designed a lab using early modern print sources, neural embeddings and close reading to analyze semantic similarities in European representations of Asian courts.

- [Letters to Networks](https://github.com/conradcompagna/letters-to-networks): designed a correspondence-network lab with historical letters, annotation exercises and an interactive explorer teaching students how to build and interpret edge graphs.



## Content specialisms

Global and imperial history; South, Southeast and East Asia since 1500; the East India Company; comparative empire; borderlands; indigenous agency; colonial knowledge; digital humanities; natural language processing; computational linguistics; LLM engineering.

## Skills and languages

**NLP:** Hugging Face Transformers; PyTorch; TensorFlow; CUDA; neural network architectures; corpus construction; dataset construction; model training and evaluation; runtime quantization; tokenization; morphological analysis; dependency parsing; named-entity recognition; vector embeddings; semantic search; agent orchestration.

**Software and data:** Python; JavaScript; Node.js; HTML/CSS; Flask; SQLAlchemy; SQLite; REST APIs; Linux; Gunicorn; Nginx; dynamic programming; knowledge graphs; RDF; SPARQL; Oxigraph; corpus analysis; data visualization.

**Applied LLM engineering:** Codex; Claude Code; CLI environments; prompt engineering; context-window management; multi-agent orchestration; Git management; review and QA; LLM API integration; structured outputs.

### Languages

**Mandarin Chinese:** advanced speaking and reading proficiency.

**Burmese and French:** reading proficiency.
