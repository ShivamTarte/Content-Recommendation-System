# Content-Recommendation-System(SBERT)
This is  project named LECR Recommendation system based on kaggle competition i performed and succesfully submitted by using (SBERT)sentence transformer,Annoy index and Fuzzy logic.It provided with topics with its parents and content to match to each other.Recommend different contents based on topics and its parent
An example of a branch of a topic tree is: Secondary Education >> Ordinary Level >> Mathematics >> Further Learning >> Activities >> Trigonometry. The leaf topic in this branch might then contain (be correlated with) a content item such as a video entitled Polar Coordinates.

EXPLANATION-The algorithm used is SBERT which is transformer network for cosine sentence similarity.Topics and content are given as input similarity between thm found and relation is formed.Annoy index is used to recommend related contents in from numbers of millions.It is used in SPOTIFY to recommend songs and for fine tunining we use fuzzy logic to give related contents

Five datsets are used one for sentence transformer and four dataset for competition topic dataset,content dataset,correlation dataset,sample submission respectively.Relation between Topic and its parent with content is formed.At maximum 10 content is recommended for a particular topic.

DATASET LINK-Four Dataset=>https://www.kaggle.com/competitions/learning-equality-curriculum-recommendations/data
Sentence Transformer=>https://www.kaggle.com/datasets/kaizen97/sentencetransformers

Goal of the Competition-:Learning Equality - Curriculum Recommendations
The goal of this competition is to streamline the process of matching educational content to specific topics in a curriculum. You will develop an accurate and efficient model trained on a library of K-12 educational materials that have been organized into a variety of topic taxonomies. These materials are in diverse languages, and cover a wide range of topics, particularly in STEM (Science, Technology, Engineering, and Mathematics).

