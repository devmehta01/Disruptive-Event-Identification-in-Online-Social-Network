# Discovery-of-Disruptive-Events
We propose a framework which analyses user tweets and classifies them into eventful and non eventful. Eventful tweets then undergo community detection to group tweets belonging to same events together. This is followed by Keyword Extraction and Named Entity Recognition.


This thesis presents a disruptive event identification framework on the social network platform Twitter. Riots and protests, if gone out of control, can cause havoc in a country. We have seen examples of this, such as the BLM movement, climate strikes, CAA Movement, and many more, which caused disruption to a large extent. The motive behind creating this framework is to provide insights about the trending events on social media and alert the user about the potential disruptive events. There are numerous data-driven event prediction methods in the literature that employ supervised, unsupervised and semi-supervised techniques. Most of these works use explicit feature extraction techniques, such as TF-IDF, which fails to capture the semantic encoding between the words; and uses a machine learning-based classier for the event and non-event prediction.

In addition, most of these researches either use online clustering or hierarchical clustering on the event tweets. The online clustering fails to detect sub-communities among the communities and scans the data only once. In this paper, we follow the classifcation then clustering approach. First, we use a universal sentence encoder to encode the sentences in the proposed framework and a Deep Neural Network (DNN) classifer to classify event and non-event tweets. Next, community detection is used for detecting optimized event communities (clusters), and these event communities are annotated using various keyword extraction techniques. A novel approach called Iterative Neighbourhood Blending was also devised to effectively cluster the similar queries. The efectiveness of the proposed framework is validated using three datasets, showcasing that the proposed framework can successfully identify disruptive events.
