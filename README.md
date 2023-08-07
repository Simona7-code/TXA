# Text_Analytics-course_project__2023

The aim of the project was to select a linguistic dataset and:
- perform analyzes on linguistic data;
- train classifiers (from the more traditional models like Support Vector Classifier to the more complex LLMs like BertForSequenceClassification) in order to perform a single-label multiclass classification.

This task was inspired by the shared task on SemEval2023 "Detecting the gender, the framing, and the persuasion techniques in online news in a multi-lingual setup" (https://propaganda.math.unipd.it/semeval2023task3/), from whose data the necessary dataset was built in order to perform the classification of different types of persuasive communication present in the texts, for a total of 7 types.

The folder is composed as follows:
- Inside the _generation_ folder there is the notebook that allowed the creation of the dataset definitively used in order to carry out the task;
- Three jupyter notebook files containing:
    - text exploration using NLTK library methods and performing various tasks such as entity name recognition and sentiment analysis;
    - the application of different non-LLM classification algorithms.
    - the application of the BertForSequenceClassification (LLM) classification model.
- A pdf file containing the project report and the presentation of the results obtained.

############################################################################

Lo scopo del progetto era selezionare un dataset di dati linguistici e:
- svolgere delle analisi sui dati linguitici;
- addestrare classificatori (dai più tradizionali modelli come Support Vector Classifier ai più complessi LLM come BertForSequenceClassification) al fine di effettuare una classificazione multi-class single-label.   

Questa task è stata ispirata dalla task condivisa su SemEval2023 "Detecting the genre, the framing, and the persuasion techniques in online news in a multi-lingual setup" (https://propaganda.math.unipd.it/semeval2023task3/), dai cui dati è stato costrutito il dataset necessario al fine di eseguire la classificazione di diversi tipi di comunicazione persuasoria presenti nei testi, per un totale di 7 tipi.

La cartella è stata così composta:
- All'interno della cartella _generazione_ è presente il notebook che ha permesso la creazione del dataset definitivamente utilizzato al fine di svolgere il task;
- Tre file jupyter notebook che contengono:
  - l'esplorazione dei testi tramite metodi di libreria NLTK e lo svolgimento di diverse task come la name entity recogniton e sentiment analysis;
  - l'applicazione di divesi algoritmi di classificazione non LLM.
  - l'applicazione del modello di classificazione BertForSequenceClassification (LLM).
- Un file pdf che contiene la relazione di progetto e la presentazione dei risultati ottenuti.
