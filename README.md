# AINDA Project - DEBISS-Arg - Argument Mining  

Hello!  
This repository contains a branch of the AINDA project focused on developing solutions for Argument Mining (AM).  

In this repository, you will find data from debates with various AM data annotations.  

The data provided are the results of a master’s degree research project, which is fully accessible [here](https://example.com/research-document).  

## About the Data  

To construct this dataset, a comprehensive understanding of the relationship between Argument Mining and education was essential. For this purpose, a  
[survey](https://example.com/research-document) was conducted. 

Additionally, a customized annotation protocol was developed, as AM presents unique challenges for NLP due to the lack of a universally accepted framework for data annotation. The protocol can be found in the PDF file titled **"Annotation Protocol"** ([available here](https://github.com/AINDA-Project-UFCG/argument-mining-data/blob/main/protocol.pdf)).  

To increase awareness of this dataset within the scientific community and discuss its contributions in detail, the following research was developed and published:  
[DEBISS-Arg Corpus](https://example.com/research-document).  

The data was manually annotated using an annotation tool developed by the LACINA lab at UFCG. For more details on the annotation and review process, refer to the annotation protocol in the provided PDF, as well as the research conducted for the corpus.  


### The data

There is annotation for arguments and their components (premise, claim, and evidence). You can find these in the CSV files on this page. Additionally, there is annotation for relations at both micro and macro levels, with more details available in the respective folders.

Argument and Component Annotations

In the CSV file for argument and component identification, you will find the following columns:

utterance_order: The order of the utterance within the debate section.

transcription: The transcription of what was said in the utterance.

debater: The identifier of the person who spoke this piece of information in the debate.

argument_premise_evidence_claim: Argument and component annotation in the following format:

    **[('claim_1', 0, 42), ('claim_2', 55, 85)]**
    
    In this format:
    The first element in each tuple represents the annotation type (e.g., claim, premise, or evidence).
    The second element represents the start token of the label.
    The third element represents the last token of the label.
     * Obs: The tokenization process is performed using a simple split based on blank spaces.

For more details, refer to the respective CSV files and documentation in the dataset folders.

## Open Source and Research Use  

This dataset is open-source and can be freely used for research purposes.  

Enjoy! 😉  
