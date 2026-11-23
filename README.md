# Experiment 6: Named Entity Recognition (NER) using spaCy

## Overview
This experiment implements a Named Entity Recognition (NER) application using Python and the spaCy Natural Language Processing library.

A Renewable Energy Project dataset is used to automatically identify and classify named entities such as persons, organizations, geographical locations, dates and monetary values from unstructured text.

## Aim
To implement a Named Entity Recognition system using spaCy to automatically identify and classify named entities from natural language text.

## Objectives
- Understand the concept of Named Entity Recognition.
- Load a pretrained spaCy NLP model.
- Extract named entities from text.
- Identify entity categories such as PERSON, ORG, GPE, DATE and MONEY.
- Visualize recognized entities using displaCy.
- Calculate entity-type frequency distributions.
- Generate bar charts and heatmaps for entity analysis.

## Technologies Used
- Python 3
- Google Colab
- spaCy
- Pandas
- Matplotlib
- Seaborn

## Dataset
The experiment uses a sample text dataset based on Renewable Energy and Solar Power Projects.

The dataset contains information about:
- Environmental scientists
- Renewable energy organizations
- Project locations
- Event dates
- Investment amounts
- Carbon emission reduction targets

## Implementation Steps
1. Install the required Python libraries.
2. Download the pretrained spaCy model `en_core_web_sm`.
3. Import the required libraries.
4. Load the spaCy NLP pipeline.
5. Create the renewable energy text dataset.
6. Process the text using spaCy.
7. Extract named entities and their labels.
8. Generate an extracted entities DataFrame.
9. Visualize entities using displaCy.
10. Calculate entity-type frequency using Counter.
11. Create an entity frequency bar chart.
12. Generate an Entity vs. Label heatmap.
13. Display the final analysis tables.

## Installation

Install the required libraries:

```bash
pip install spacy pandas matplotlib seaborn
```

Download the pretrained spaCy model:

```bash
python -m spacy download en_core_web_sm
```

## Entity Categories

| Entity Label | Description |
|---|---|
| PERSON | Names of people |
| ORG | Organizations and institutions |
| GPE | Countries, cities and states |
| LOC | Geographical locations |
| DATE | Dates and periods |
| TIME | Time expressions |
| MONEY | Monetary values |
| PERCENT | Percentage values |

## Repository Structure

```text
NLP_Practical_Experiments/
│
├── Experiment_4_BOW_NGRAM.ipynb
├── Experiment_5_Morphological_Analysis.ipynb
├── Experiment_6_Named_Entity_Recognition.ipynb
│
├── README.md
└── README_Experiment_6.md
```

## Expected Output
The experiment generates:

- Extracted named entities table.
- Entity labels and descriptions.
- Colour-highlighted entity visualization.
- Entity-type frequency distribution.
- Entity frequency bar chart.
- Entity Name vs. Recognized Entity Type heatmap.

## Applications
- Information Extraction
- Resume Parsing
- News Analysis
- Financial Document Analysis
- Knowledge Graph Construction
- Search Engines
- Automated Document Understanding

## Result
The Named Entity Recognition system was successfully implemented using Python and spaCy. Named entities were extracted from the renewable energy dataset, organized into structured tables and analyzed using frequency distribution, bar chart and heatmap visualizations.

## Conclusion
Named Entity Recognition is an important NLP technique used to identify and classify meaningful entities from unstructured text. This experiment demonstrated how spaCy's pretrained model can extract entities, organize information and visualize entity distributions without requiring additional model training.

---

**Tools:** Python | spaCy | Pandas | Matplotlib | Seaborn | Google Colab
