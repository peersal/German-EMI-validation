# German-EMI-Validation

## Overview
Welcome to the German-EMI-Validation repository! This repository documents the progress of the validation process for the German Evidence Minus Intuition (EMI) score.

## Project Description
In this project, we utilize two datasets from the German Parliament to train a word2vec model. This model helps vectorize two dictionaries: one associated with evidence-based language and the other with intuition-based language. By calculating the distance between German parliamentary speeches and these dictionaries, we ultimately derive an Evidence Minus Intuition (EMI) score.

## Datasets
The project employs the following datasets:

1. **German Parliament Data (1867 to 1942)**: [GerParCor](https://github.com/texttechnologylab/GerParCor?tab=readme-ov-file)
2. **German Parliament Data (1949 to 2021)**: [Open Discourse](https://github.com/open-discourse/open-discourse)

Find all of the datasets of this project here OSF link to come 


## Methodology
1. **Data Collection**: Collect data from the two provided datasets.
2. **Model Training**: Train a word2vec model using the collected data.
3. **Dictionary Vectorization**: Vectorize two dictionaries—one for evidence-based language and one for intuition-based language.
4. **EMI Score Calculation**: Calculate the distance between parliamentary speeches and the dictionaries to derive the EMI score.
5. **Validation**: Validate the EMI score using a sample of German parliamentary texts annotated in a survey.

## Dictionary Validation
The dictionaries used in this project were validated by Segun Aroyehun. For more information about the dictionaries, please reach out to Segun Aroyehun at [segun.aroyehun@uni-konstanz.de](mailto:segun.aroyehun@uni-konstanz.de).

## Contact Information
For further questions or inquiries, please reach out to:

- Peer Saleth: [peer.saleth@uni-konstanz.de](mailto:peer.saleth@uni-konstanz.de)

Thank you for your interest in the German-EMI-Validation project! We look forward to your contributions and feedback.
