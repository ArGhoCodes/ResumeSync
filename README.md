# Resume-Matching-with-Job-Description-from-CVs
Project Overview

Data Collection and Preparation:
A dataset containing PDFs of live resumes from a job portal was made available via a web link.
I extracted information from these PDF resumes and meticulously organized the data into a structured CSV file.

Job Descriptions:
To complete the puzzle, I collected job descriptions from various companies, sourced from Kaggle and provided in CSV format through a data link.

Data Preprocessing:
Ensured that both resume and job description data were cleaned, pre-processed, and tokenized to facilitate further analysis.

Embedding Using DistilBERT:
To unlock the power of contextual embeddings, I utilized DistilBERT, a state-of-the-art language model, to transform the textual data into meaningful numerical representations.

Cosine Similarity Analysis:
Here comes the magic! I computed cosine similarity scores between job descriptions and resumes to determine how well they match.
The top 5 resumes with the highest cosine similarity scores were selected as the most suitable candidates for each job.

Methodology:
1. PDF extraction with PyPDF2 or PDFMiner.
2. Text tokenization and embedding using DistilBERT from Hugging Face.
3. Cosine similarity calculation for candidate-job matching.

Contact:
arpanghosh5115@gmail.com

