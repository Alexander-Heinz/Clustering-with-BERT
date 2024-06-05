# Arbeitsprobe Alexander Heinz

## Title: Deep Language Model Representation of Document Clustering

### Abstract (automatisch erstellt): 
Dieses Notebook umfasst einen vollständigen Workflow zur Verarbeitung und Analyse von Textdaten mit Hilfe von Natural Language Processing (NLP) und Machine Learning Methoden, insbesondere unter Verwendung von BERT- und BERTopic-Modellen. Der Prozess beginnt mit dem Import der erforderlichen Bibliotheken und der Installation der benötigten Pakete. Nach dem Einlesen der Daten aus einer Excel-Datei folgt die Datenvorbereitung, die verschiedene Schritte wie das Entfernen von Stoppwörtern, Tokenisierung und Lemmatisierung beinhaltet, wobei die Notwendigkeit dieser Schritte im Kontext von BERT diskutiert wird.

Die explorative Datenanalyse (EDA) umfasst die Visualisierung der Textlängenverteilung. Anschließend wird die Kosinusähnlichkeit der Dokumente berechnet und als Heatmap dargestellt. Das Clustering der Texte erfolgt mittels K-Means, wobei die optimale Anzahl der Cluster durch die Elbow-Methode bestimmt wird. Die Cluster werden durch eine PCA-Reduktion auf zwei Dimensionen visualisiert.

Für das Clustering und die Themenmodellierung wird das BERTopic-Modell verwendet und mit einem manuellen Ansatz verglichen. Dieses Modell nutzt Transformer-basierte Embeddings, UMAP für die Dimensionalitätsreduktion und HDBSCAN für die Clusterbildung, gefolgt von c-TF-IDF zur Reduktion und Verbesserung der Topic-Kohärenz. Die resultierenden Themen werden visualisiert und die Dokumente entsprechend den identifizierten Themen geclustert. Schließlich werden die Ergebnisse in einer Excel-Datei gespeichert und visualisiert, um eine detaillierte Überprüfung und weitere Analysen zu ermöglichen.



### Code Implementations:
* Prerequisites:
    * Python 3.7 or later
    * Jupyter Notebook


* Dependencies:
    The project uses multiple python libraries, which are required to run this code. To install the code, please run the below code snippet in the anaconda prompt.

    `pip install -r requirements.txt`

* Python Notebook:  `Arbeitsprobe_Alexander_Heinz.ipynb`