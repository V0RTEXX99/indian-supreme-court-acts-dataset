# Indian Supreme Court Judgments Dataset (Section-wise)

## Overview
This dataset contains Indian Supreme Court Acts split into smaller sections (chunks) for easier processing and analysis. Each row corresponds to a portion of a legal document, making it suitable for Natural Language Processing (NLP) tasks.

## Structure
The dataset is provided in both JSONL and CSV format with the following fields:

- chunk_id: Unique identifier for each chunk
- type: Type of document (e.g., judgment, act)
- name: Name of the case or legal document
- section: Section or logical division
- text: Content of the section
- text_length: Number of characters in the text (Only in csv file for convenience)

## Use Cases
- Legal text analysis
- Semantic search systems
- Question answering systems
- Retrieval-Augmented Generation (RAG)
- Text summarization
- Machine learning on legal corpora

## Data Source
- Legal texts for Acts have been collected from the official Indian government website: India Code (https://www.indiacode.nic.in/)
- Additional legal documents are compiled from publicly available sources.
- The original content is owned by the Government of India and is subject to applicable copyright and usage policies.

## Notes
- Text is segmented for usability.
- Some formatting inconsistencies may exist.
- This dataset is intended for research and educational purposes.

## License
Please ensure compliance with applicable data usage laws and regulations.
This dataset is released under the Apache 2.0 License for the structure and preprocessing.
The original legal texts are sourced from publicly available government resources (India Code) and are subject to their respective terms of use.

## Citation
If you use this dataset, please cite:
Aayan Iqbal. Indian Legal NLP Dataset (2026).