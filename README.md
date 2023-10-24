# Awesome Entity Resolution Resources [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

- [Open-Source Software](#open-source-software)
    - [End-to-End Entity Resolution](#end-to-end-entity-resolution)
    - [Evaluation](#evaluation)
    - [String Comparison](#string-comparison)
    - [Embeddings](#embeddings-focused-pairwise-comparison)
    - [Data Cleaning and Parsing](#data-cleaning-and-parsing)
    - [Data Quality Control](#data-quality-control)
    - [Blocking, Candidate Selection, and Search](#blocking-candidate-selection-and-search)
- [Commercial Solutions](#commercial-solutions)
- [Books](#books)

---

## Open-Source Software

### End-to-End Entity Resolution

- [Splink](https://github.com/moj-analytical-services/splink) (Python, SQL, Spark) - Scalable Fellegi-Sunter and rule-based entity resolution using your choice of SQL or Spark backend.
- [Zingg](https://github.com/zinggAI/zingg) (Python, Java) - Scalable, active learning model for entity resolution.
- [dedupe](https://github.com/dedupeio/dedupe) (Python) - Active learning and flexible Python tooling for entity resolution. 
- [PyJedAI](https://github.com/AI-team-UoA/pyJedAI) (Python, Java) - State-of-the-art entity resolution clustering algorithms.
- [DeepMatcher](RecordLinkage) (Python) - Deep learning-based entity ersolution
- [FastLink](https://github.com/kosukeimai/fastLink) (R) - Easy, scalable Fellegi-Sunter entity resolution on your laptop.
- [RecordLinkage](https://github.com/J535D165/recordlinkage) (Python) - Toolkit for prototyping entity resolution systems.
- [dblink](https://github.com/cleanzr/dblink) (R, Spark) - Scalable Bayesian graphical entity resolution.
- [exchanger](https://github.com/cleanzr/exchanger) (R, C++) - More flexible Bayesian graphical entity resolution on your laptop.
- [RELAIS](https://www.istat.it/en/methods-and-tools/methods-and-it-tools/process/processing-tools/relais) (R, SQL, Java) - Record linkage software used at the Italian National Statistics Institute.

### Evaluation

- [ER-Evaluation](https://github.com/Valires/er-evaluation) (Python) - End-to-End evaluation, including summary statistics for monitoring, principled performance metric estimators, and error analysis.
- [clevr](https://github.com/cleanzr/clevr) (R) - Performance metrics and error tables.

### String Comparison

- [jellyfish](https://github.com/jamesturk/jellyfish) (Python, C) - Fast string distance and phonetic matching.
- [py_stringmatching](https://github.com/anhaidgroup/py_stringmatching) (Python, C) - Large set of string comparison functions and tokenizaztion methods.
- [textdistance](https://github.com/life4/textdistance) (Python) - Very large collection of sequence comparison functions, including token-based distances.
- [SecondString](https://secondstring.sourceforge.net/) (Java) - Java implementation of string comparison functions.
- [StringCompare](https://github.com/OlivierBinette/StringCompare) (Python, C++) - Time and space efficient implementation of common string distance functions. Architectured for maintainability and extendability.
- [Comparator](https://github.com/ngmarchant/comparator) (R, C++) - Efficient string comparison functions in R.


### Embeddings (for pairwise comparison)

- [Entity Embed](https://github.com/vintasoftware/entity-embed) (Python, PyTorch) - Pytorch text embedding model for blocking.
- FaceNet-PyTorch (Python, PyTorch) - Embeddings for facial identity resolution.

### Data Cleaning and Parsing

- [libpostal](https://github.com/openvenues/libpostal) (C, and bindings for Python, Java, Go, Ruby, PHP, and NodeJS) - Multinational address parsing.
- [Ftfy](https://github.com/rspeer/python-ftfy) (Python) - Fixes text (unicode artifacts) for you.
- [PyJanitor](https://pyjanitor-devs.github.io/pyjanitor/) (Python) - Clean code for clean data
- [python-nameparser](https://github.com/derek73/python-nameparser) (Python) - Separate names into individual components.
- [Nominally](https://github.com/vaneseltine/nominally) - Name parser for record linkage.

### Data Quality Control

- [GreatExpectations](https://docs.greatexpectations.io/docs/) (Python) - Data quality checks.
- [validate](https://github.com/data-cleaning/validate) (R) - Data quality checks in R.

### Blocking, Candidate Selection, and Search

- [ElasticSearch](https://github.com/elastic/elasticsearch) - Search text.
- [DeezyMatch](https://github.com/Living-with-machines/DeezyMatch) (Python) - Deep embedding and approximate nearest-beighbor blocking for entity resolution.
- [StarSpace](https://github.com/facebookresearch/StarSpace) (C++, Python) - Embedding model suitable for similarity learning.

## Commercial Solutions

- AWS Entity Resolution - 
- Google Cloud Entity Reconciliation
- Senzing - 
- Amplify
- Quantexa
- Semandex
- Dataladders Data Match
- WinPure Clean and Match

## Books

- [Hands-On Entity Resolution with Splink](https://www.oreilly.com/library/view/hands-on-entity-resolution/9781098148478/) - Practical entity resolution with Splink and cloud computing.
- [Linking Sensitive Data](https://link.springer.com/book/10.1007/978-3-030-59706-1) - Introduction to privacy-preserving record linkage.
- [The Four Generations of Entity Resolution](https://link.springer.com/book/10.1007/978-3-031-01878-7) - Review of academic research in the field.
- [Data Matching: Concepts and Techniques for Record Linkage, Entity Resolution, and Duplicate Detection ](https://link.springer.com/book/10.1007/978-3-642-31164-2)
