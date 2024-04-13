# Hateful Communication Review Dataset

ReadMe for the hateful communication review dataset from Yu et al. (Accepted). This paper presents a systematic literature review of the past decade of papers that introduce datasets meant for training machine learning models for detecting hateful language, focusing on the included identities that shape the production of hateful communication datasets. 

If you use this dataset or any results from the analysis, please cite our paper under review. If you have any questions, please contact the response author MSc Zehui Yu for feedback: zehui.yu at gesis.org. 

The full author list can be found below:
Zehui Yu (GESIS, RWTH Aachen), Indira Sen (RWTH Aachen, Kostanz University), Dennis Assenmacher (GESIS), Mattia Samory (Sapienza - Università di Roma), Leon Fröhling (GESIS, RWTH Aachen), Christina Dahn (GESIS), Debora Nozza (Bocconi University), and Claudia Wagner (GESIS, RWTH Aachen). 

## Dataset descriptions

Hate Review_cleaned_v16.csv is the full dataset used in the paper for the special issue of the Social Science Computer Review journal.

HateReview_1.csv removes unqualified entries based on a few filtering questions, including duplicated results, dataset creation, and accessibility. Duplicates are either from the paper downloading step using search queries since we downloaded the paper from different sources or manual annotations due to repeated annotation. In terms of the dataset, the included datasets should be newly created or adapted and accessible to researchers for the use of further research. 

## Overview

The Hate Speech Review Dataset is provided in a general table with 63 variables. It is divided into four main sections as below:

### Administrative Variables

'id' is the unique ID number assigned to the publication.

### Characteristics of Papers

'reference' is the recommended way to refer to the publication while writing.

'Title of the paper' is the full title of the publication under review.

'Journal' indicates the journal or conference name that the paper is published in.

'Researcher location' is the country/region of the institute that the authors of the publication are affiliated with.

'Summary of the Paper' is a summary of the paper, including its main research purpose, research question, research methods adopted, dataset details, results, and contributions. 

'citations' is the number of citations of the publication at the time of annotation. Google Scholar is used as the standard platform for the citation number.

'Publication' indicates the specific publication date of the paper under review (e.g., 31.08.2017). If the day or month is not clear or cannot be found, it will be replaced by XX.

'Fill-in date' indicates the specific date when you fill in the matrix (e.g., 31.08.2022). If the day or month is not clear or cannot be found, it will be replaced by XX.

### Characteristics of Datasets

#### Construct operationalization

'Construct definition' is the construct definition of the main concept (e.g., hate speech) or related topic used by the authors for the dataset collection. If there is no clear definition clarified in the literature, only the topic is entered here.

'Sub-category' is a yes/no binary variable, indicating whether or not there is a sub-category under the main topic of the dataset annotated. If the answer is confirmed, the next variable 'Sub-category_1_1TEXT' will have an answer.

'Sub-category_1_1TEXT' is the specific category of the main topic clarified in the dataset.

#### Data collection

'availability of data' is a yes/no binary variable, indicating whether or not the dataset can be accessed. If the answer is confirmed, the source will be annotated as 'format of dataset'.
 
'format of dataset' is a categorical variable, indicating the access way of the dataset. According to the results from the pre-test annotation practice, it has three values: Github, Website, and Other. If 'Other' is entered here, it will be clarified as 'format of dataset_3_TEXT'.

'format of dataset_3_TEXT' is the entry of the 'Other' access way of the dataset.	

'how to access' indicates where the dataset can be found and downloaded.

'verification of the way to access' is a yes/no binary variable, indicating if the provided way to access the dataset is valid or not.

'reference of dataset' indicates how the dataset is referred to in the paper (e.g., HASOC).

'Number of datasets in use' is a numerical variable, indicating the total number of datasets that are being analyzed by the research when there is more than one dataset included in the research.

'Number of new datasets' is a numerical variable, indicating the total number of datasets that are newly created or adapted by the research.	

'Data source' is a categorical variable, indicating where the data is collected from, such as the media source or any other platform the data is oriented from. (e.g., Facebook; Fora).	

'topical focus' is a categorical variable, indicating the main topic of the dataset related to hate speech that the publication focused on (e.g., Abusiveness; Aggressiveness).

'Language' is a categorical variable, indicating the language of the data in the dataset being analyzed in the paper: If multiple languages are included, all of them will be indicated by referring to the reference name as above; If there is no mention of the language, English will be considered as the default answer.	

'Time span of data collection' indicates the time when the data is collected, using a specific date span, such as 10.01.2022 – 20.01.2022.

'data production' is the time when the data is produced, using a specific date span, such as 10.01.2022 – 20.01.2022.

'Country/ region span' is a categorical variable, indicating the country or region where the data is collected from.

'Events' indicates the involved event if the data is collected to study a particular event in association (e.g., #MeToo, #BLM).

'Data collection procedure' specifies the strategy used for collecting the dataset (e.g., which kind of API, using keyword, etc.).

'anonymity of data' is a yes/no binary variable, indicating whether or not the researchers take any steps to protect the anonymity of data sources while collecting data. If the answer is confirmed, it will be specified as 'anonymity data_1_TEXT'. 

#### Annotation

The detailed information about the annotation of the dataset, including its 'Annotation type', 'annotation schema' if available, 'sampling strategy' if available, 'annotation number' of the dataset, number of the annotations used for training and testing, 'Annotators	guideline' if available, and	'Incentives' for the annotators	if available.

### Characteristics of Targets

'General or specific' is a binary variable, indicating if the paper studies hateful content that expresses negativity in a general manner or against targets from a specific community based on the annotation procedure and results, values: general, specific.

'Reported' indicates all the target groups based on a general level.

'Targeted or non-targeted'	is a binary variable, indicating if the paper studies hateful content based on the construct definition and concept description.

'Content producer' is a binary variable, indicating whether it is human or non-human (e.g., bots) that produced the hateful content.





