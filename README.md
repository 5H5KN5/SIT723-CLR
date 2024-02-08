# SIT723 CLR
## A computational literature review of health psychology intervention development

This GitHub Repository contains the notebooks and data required to conduct a computational literature review of health psychology intervention development. 

The Content Analysis.ipynb notebook contains the code to perform topic modelling with BERTopic. 

The Impact Analysis.ipynb contains the code to conduct a scientometric analysis. 

The Data structure is as folows:
Data contains two folders: Content and Impact. 
Content>Articles>PDF contains the raw PDF files of the screened literature. Content>Articles>tsv contains a tsv file of the literature corpus. 
Content>Articles>txt contains the text files of raw text extracted from the PDF files. 
Content>Articles>txt>preprocessed contains the preprocessed txt files extracted from the raw txt files.

Impact>Bib contains the .bib bibliographic file containing the articles from the literature screening used for the scientometric analysis.
Impact>Bib> Journals contains .bib biliographic files for the individual journals in the dataset.
Impact>Journal CSV Files Contains the Merged CSV File and the Raw CSVs of journal impact factor extracted from the Web of Science Website.

Feel free to use and adapt this code as you see fit 🤙
