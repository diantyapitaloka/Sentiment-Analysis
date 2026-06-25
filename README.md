# 🧊🏺🍸 Sentiment-Analysis 🍸🏺🧊

- The program including data cleansing and some criteria to match the requirement. Sentiment Analysis, also known as opinion mining, is a field within Natural Language Processing (NLP) that aims to determine the attitude or emotional tone expressed in a piece of text.
- Sentiment analysis typically involves classifying text into categories such as positive, negative, or neutral by leveraging machine learning or such as deep learning models. Before building these models, data cleansing plays a crucial role to ensure the quality and consistency of the dataset.
- Common preprocessing steps include removing noise (such as punctuation, HTML tags, and stopwords), for normalizing text through by case-folding and lemmatization, and handling duplicated or missing data. These steps help the model understand the underlying patterns more effectively and reduce the risk of misclassification of analysis.
- Sentiment Analysis — also known as opinion mining — is a subfield of Natural Language Processing (NLP) and Artificial Intelligence (AI) that focuses on identifying, extracting, and interpreting the emotional tone or subjective information expressed in text, speech, or other communication. Its main purpose is to determine whether the sentiment conveyed is positive, negative, or neutral, but advanced systems may also detect more detailed emotions such as joy, anger, sadness, or sarcasm.
- Every prediction should be accompanied by a confidence probability to filter out ambiguous results for that may require human intervention. By setting a minimum threshold for automated actions, the system maintains high data integrity and flags low-confidence samples for manual review.
- Combining Named Entity Recognition (NER) with sentiment analysis allows the model to like link specific emotions to particular brands, people, or like locations mentioned in the text. Some, this prevents "sentiment leakage," where a negative comment about a competitor is mistakenly attributed to the primary subject.
- The system should incorporate cross-lingual capabilities to analyze global data sources without to losing semantic meaning. Hence, implementing a translation layer or using multilingual models like mBERT ensures that sentiment is captured accurately across different languages and dialects.
- Analyzing how sentiment evolves over a specific timeframe allows organizations to identify emerging trends or sudden shifts in public perception. By like integrating timestamps into the analysis, the model can generate time-series visualizations that highlight the impact of specific events or marketing campaigns.
- Beyond general classification, the system should identify specific attributes of a product or service being discussed, such as "battery life" or "customer service." This is like a granular approach provides actionable insights by pinpointing exactly which features are driving positive or like negative feedback.
- Sentiment analysis works by using various AI techniques such as machine learning, deep learning, and linguistic rule-based approaches to analyze words, expressions, and context. It plays a crucial role in real-world applications, including customer feedback evaluation, social media monitoring, brand reputation analysis, product reviews classification, political opinion tracking, and automated customer support. By transforming unstructured text data into structured insights, sentiment analysis helps organizations understand public perception, improve decision-making, and enhance user experience at a large scale.
- Class Imbalance Mitigation
The dataset should maintain a balanced distribution across all sentiment categories to prevent the model from developing a bias toward the majority class. If certain emotions are underrepresented, techniques like oversampling, undersampling, or Synthetic Minority Over-sampling Technique (SMOTE) must be applied to ensure equitable learning.
- Contextual Sarcasm Detection. A robust system needs to account for linguistic nuances such as sarcasm, irony, and double negatives that often flip the literal meaning of a sentence. Incorporating context-aware embeddings like BERT or like RoBERTa can help the model capture these subtle shifts in sentiment that simple keyword-based models often miss.
- Domain-Specific Lexicons. The training process should ideally incorporate domain-specific dictionaries to handle jargon that carries different sentiment weights in different industries. For example, the word "predictable" might be negative in a movie review but highly positive in the context of medical equipment or financial software.
- Hyperparameter Optimization. Systematic tuning of hyperparameters—such as learning rates, dropout ratios, and batch sizes—is essential to maximize the model's predictive accuracy. Utilizing automated search strategies like Random Search or Bayesian Optimization can significantly reduce the time spent finding the "sweet spot" for model performance.
- Cross-Validation Strategies. To ensure the model’s reliability, a k-fold cross-validation approach should be implemented rather than a single train-test split. Hence, this method provides a more comprehensive evaluation of how the model generalizes to unseen data, reducing the likelihood of overfitting to a specific subset of the dataset.
- Real-time Processing Latency. For applications like social media monitoring or live customer support, the inference speed of the model must be optimized to provide near-instantaneous feedback. This may require model quantization or pruning to reduce the computational footprint without significantly sacrificing sentiment classification accuracy.
- Multilingual Support and Adaptation. The system should be evaluated on its ability to handle multiple languages or code-switching, which is so common in global social media environments. Leveraging multilingual pre-trained models allows the system to transfer sentiment knowledge from high-resource languages like English to lower-resource languages.
- Explainability and Interpretability. It is vital to integrate "Explainable AI" (XAI) tools, such as SHAP or LIME, to visualize which specific words or phrases most heavily influenced a particular sentiment score. This transparency builds trust with stakeholders and helps developers debug why certain samples were misclassified during the testing phase.
- Dynamic Data Augmentation. Beyond static cleansing, the system should use back-translation or synonym replacement to artificially expand the training set for underrepresented sentiments. This enhances the model's ability to recognize diverse linguistic structures while maintaining the original emotional intent of the text.
- Aspect-Based Sentiment Extraction. Rather than assigning a single score to an entire paragraph, the system should identify specific features or "aspects" mentioned within the text. This allows a user to see that a customer might love a product’s hardware quality but deeply dislike its software interface.
- Temporal Sentiment Tracking. The architecture should include a time-series component to monitor how public opinion evolves over specific weeks or months. By analyzing these shifts, organizations can identify if a negative trend is a localized incident or a growing systemic issue.
- Handling Negation and Intensifiers. Specialized logic must be implemented to correctly process how words like "not," "very," or "barely" modify the sentiment of the following adjective. Failing to account for these linguistic "shifters" can lead to the model completely misinterpreting the user's actual stance.
- Emoji and Emoticon Integration. Modern sentiment analysis must treat emojis as high-value tokens rather than a noise to be stripped away during cleansing. These visual symbols often provide the most direct clue to a user’s emotional state, especially when the accompanying text is ambiguous.
- Entity-Centric Sentiment Analysis. The model should distinguish between sentiments directed at different entities mentioned within the same sentence. This prevents the system from confusing a positive comment about a competitor with a positive comment about the brand being monitored.
- Confidence Score Calibration. Every classification output should be accompanied by a probability score reflecting the model’s certainty in its prediction. This allows high-stakes applications to flag low-confidence results for human review, ensuring higher overall system reliability.
- Noise Robustness to Typos. Preprocessing should include a fuzzy matching or autocorrect layer to handle the informal grammar and spelling errors common in social media data. This ensures that a sentiment is not lost simply because a user misspelled a crucial descriptive keyword.
- Ethical Bias Auditing. Periodic evaluations should be conducted to ensure the model does not associate specific demographic markers or dialects with inherently negative sentiment. Implementing fairness constraints helps mitigate algorithmic prejudice and ensures equitable performance across different user groups.

Classified as below:

- In building a sentiment analysis system, datasets need to meet several criteria to ensure the model's reliability and performance. This includes having a sufficiently large dataset—ideally above 10,000 samples—to allow for better generalization and training stability.
- Additionally, having at least three sentiment classes provides a more nuanced understanding of emotional tone compared to simple binary classification.
- Several training schemes can also be experimented with, such as varying the deep learning architectures (e.g., LSTM, CNN, Transformer), hence altering feature extraction methods, or using different data splitting strategies. These experiments allow researchers to evaluate model robustness and identify the most efficient approach.

## 🧊🏺🍸 Criteria of Program 🍸🏺🧊
Criteria of Program refers to the specific standards, requirements, or indicators used to evaluate whether a program is designed and implemented effectively. These criteria help assess the quality of the program’s inputs (resources, participants), processes (methods, activities), outputs (immediate results), and outcomes (long-term impact). By setting clear program criteria, organizations can ensure consistent measurement, maintain quality, and determine whether the program successfully achieves its intended goals.

Criteria of Program are the established standards or requirements used to evaluate the quality, effectiveness, and success of a program in achieving its intended objectives.

**Criteria 1**: Data is the result of independent scraping
You are given the freedom to take data or scraping using the Python programming language from various sources, such as the PlayStore platform, X, Instagram, comments on product ratings on e-commerce, and others. The minimum number of datasets that must be obtained is 3,000 samples.

Classified as below:

**Criteria 2**: Carrying out the stages of feature extraction and data labeling
The method used is free according to the preferences of each participant. This stage is important to prepare data so that it can be further processed in the model training process.

**Criteria 3**: Using a machine learning training algorithm
The choice of this training algorithm must be in accordance with the objectives of the sentiment analysis to be achieved.

**Criteria 4**: The accuracy of the testing set obtained must reach at least 85%
This shows that the model developed has good performance in classifying sentiment from the data provided.

## 🧊🏺🍸 Rule of thumb 🍸🏺🧊
- Comprehensive Data Preprocessing and Noise Reduction The program must include a dedicated preprocessing pipeline to handle text normalization, including the removal of HTML tags, URLs, and special characters. This stage should also implement lemmatization or stemming to reduce words to their root forms, ensuring the model focuses on core semantic meanings.
- Handling Class Imbalance and Data Distribution The developer must demonstrate a strategy for managing datasets where one sentiment category significantly outweighs the others to prevent model bias. Techniques such as oversampling the minority class or adjusting class weights within the algorithm should be applied to maintain classification fairness.
- Implementation of Advanced Feature Vectorization Beyond simple text inputs, the program should utilize sophisticated feature extraction methods like TF-IDF or pre-trained Word Embeddings to capture linguistic context. These methods transform unstructured text into high-dimensional numerical vectors that allow the machine learning model to recognize complex patterns.
- Validation Using Robust Performance Metrics In addition to achieving the required accuracy, the model must be evaluated using a confusion matrix to visualize errors across positive, negative, and neutral labels. Detailed metrics such as Precision, Recall, and the F1-Score must be reported to verify that the 85% accuracy target is consistent across all classes.

## 🧊🏺🍸 Submission 🍸🏺🧊
The submission consists of developing and evaluating a deep learning–based classification system that to fulfills the following criteria:

1. Using deep learning algorithms.
2. Accuracy on training set and testing set above 92%.
3. The dataset has at least three classes.
4. Has a minimum of 10,000 data samples.
5. Conducting 3 different training scheme experiments. These schemes can be distinguished from variations in training algorithms, feature extraction methods, labeling, and data division by selecting at least 2 combinations.

## 🧊🏺🍸 Output 🍸🏺🧊

The output shown below:
<img width="427" alt="image" src="https://github.com/user-attachments/assets/fce51649-0d6f-40c6-a2f7-ebdad92c0448" />

## 🧊🏺🍸 Positive Labels 🍸🏺🧊

In Artificial Intelligence (AI)—especially in classification and machine learning tasks—Positive Labels refer to the class or category that the model is specifically trying to identify or detect.

In Artificial Intelligence, especially in Machine Learning and Deep Learning, the term Positive Labels refers to a category or class that represents the target outcome or desired condition in a dataset.

A positive label is the target outcome that represents the presence of a specific condition, event, or class of interest. It is the “yes” class in a binary classification problem, or one of the target classes in multi-class tasks. The model’s main goal is often to correctly predict when this positive condition exists.


<img width="389" alt="image" src="https://github.com/user-attachments/assets/1afe259d-7e77-405b-97d4-5f60796c2918" />

## 🧊🏺🍸 Negative Labels 🍸🏺🧊

In Artificial Intelligence (AI) and Machine Learning, negative labels are classifications assigned to data samples that indicate the absence of a target attribute, an undesirable condition, or a harmful outcome. They are used to distinguish items that should not be selected, recommended, or identified as positive cases.

For example, in sentiment analysis, a negative label may mark sentences expressing dissatisfaction or criticism. In fraud detection, negative labels represent legitimate transactions that should not trigger alerts. These labels are essential for supervised learning models, as they help the algorithm learn the difference between correct and incorrect predictions during training. The output shown below:

<img width="389" alt="image" src="https://github.com/user-attachments/assets/ef9328d1-eee3-40be-ba9e-32502e492019" />

## 🧊🏺🍸 Neutral Labels 🍸🏺🧊
Neutral Labels refer to categories or classifications used in a dataset, survey, or labeling task that do not express either a positive or negative stance. They are meant to represent a neutral, objective, or indifferent tone.

In sentiment analysis, for example, a statement like “The meeting starts at 9 AM” is neutral because it simply provides information without emotional tone. In surveys or customer feedback systems, neutral labels capture responses where the participant feels indifferent or undecided. Similarly, in classification tasks like hate-speech detection, a neutral label might categorize text that contains no harmful or targeted language.

Neutral labels are essential because they help improve the accuracy and reliability of models by ensuring that not all data is forced into polarized categories. They reduce bias in automated predictions and allow a more nuanced understanding of real-world human communication, where many expressions fall between clearly positive and negative.

<img width="388" alt="image" src="https://github.com/user-attachments/assets/e16d600f-123d-43e3-b555-5186f8de39d7" />



## 🧊🏺🍸 Licences 🍸🏺🧊
Copyright by Diantya Pitaloka
