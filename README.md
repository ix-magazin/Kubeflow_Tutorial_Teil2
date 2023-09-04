# Mit Kubeflow und Evidently Modell-Endpunkte erstellen und überwachen
Code aus dem zweiten Teil des Kubeflow-Tutorials von Pavol Bauer, erschienen auf [heise+](https://heise.de/-9240128) und in [Ausgabe 09/2023](https://www.heise.de/select/ix/2023/9/2315907591704974604) des [iX-Magazins](https://www.heise.de/select/ix/2023/9/).

# iX-tract
- Mit Kserve lassen sich APIs und Endpunkte für Modelle in Kubeflow-Pipelines bereitstellen. Diese empfangen Eingabedaten und geben Vorhersagen der bereitgestellten Modelle an die Anwender zurück.
- Sobald das Modell auf dem Endpunkt ist, beginnt das Monitoring. Hier ist die Open-Source-Bibliothek Evidently eine gute Wahl, um auf Modell- und Datendrift reagieren zu können, die die Ergebnisse der Modelle mit der Zeit verfälschen.
- Mit einem Custom Model Server lassen sich auch Modelle in Kserve einbinden, für die es in den gängigen Schnittstellen noch keinen Anschluss gibt. Hierdurch kann man beispielsweise die ganze Stärke der Hugging-Face-Transformers-Bibliothek ausspielen.

# Listings
- Tutorial2: Kserve and Evidently for model serving and monitoring
  - Listing1: Creation of Kserve Sklearn server
  - Listing2: Querying the Kserve Sklearn server
  - Listing3: Drift and performance monitoring with Evidently
  - Listing4: Kserve custom model serving with Q&A BERT model powered by HuggingFace
  - Listing5-6: Querying the custom Kserve model
