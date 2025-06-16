
# Analysis-of-Emotional-Expressions-in-Sinhala-Music-Video-Comments-on-YouTube

Understanding and classifying emotions on social media is important for many areas such as sentiment analysis, product improvement, social science studies, personalized recommendations, and even monitoring mental health.
This study focuses on recognizing emotions in Sinhala comments on YouTube songs. The study uses Russell’s Valence-Arousal (V-A) model, which provides a deeper understanding of emotions than just labeling them as positive or negative. This model explains emotions using two dimensions: valence (how pleasant or unpleasant an emotion is) and arousal (how intense or calm the emotion is). By placing comments in this two-dimensional space, we can better visualize and analyze emotional responses to different songs.
One of the main contributions of this research is the creation of a new dataset called GeeSanBhava. The name is a combination of three Sinhala words: Gee (songs), San (short for comments), and Bhava (emotion). The dataset contains 63,471 Sinhala song comments, manually labeled with different emotional categories. These comments were annotated by three independent reviewers, who reached a high agreement rate of 84.96%, showing the consistency and reliability of the labeling process.
This is currently the largest and most comprehensive dataset for Sinhala sentiment and emotion analysis using the Valence-Arousal approach.
The study also explores the connection between the emotions found in user comments and the emotional tone of the songs themselves. Using cosine similarity, it looked at how user reactions match with expert assessments of the songs' emotions. Since user comments can be influenced by personal preferences, social settings, or other comments, this comparison helps highlight differences between the music's intended emotion and how it is perceived by listeners.
Finally, the study focussed on training and evaluated several machine learning and deep learning models to classify the emotions in Sinhala comments. The most successful model was a Multi-Layer Perceptron (MLP), which achieved a strong ROC-AUC score of 0.887.
This research offers both a valuable resource for future Sinhala language studies and meaningful insights into how music triggers emotional responses.


## Data Set Description

Description of Songs

This study gathered Sinhala-language comments from a wide range of YouTube music videos, featuring songs produced across different time periods. By including music from various eras, the dataset captures listener responses from diverse age groups and backgrounds. This rich and varied collection offers valuable insights into how Sinhala music is emotionally experienced and interpreted by audiences over time, contributing to a deeper understanding of cultural and generational perspectives in digital music engagement. Below table summarise the genres of the music videos considered in the study.


| Song Index | Song Name                  | Song Genre         |
| :--------- | :------------------------- | :----------------- |
| S01        | Ambaruwo                   | Folk               |
| S02        | Amude                      | Folk               |
| S03        | Ansathu Oba                | Mordern Pop Music  |
| S04        | Ape Hagumwalata            | Classic Pop Music  |
| S05        | Danena Thuru Maa           | Modern Pop Music   |
| S06        | Dannawada Adare Neethiya   | Pop Music          |
| S07        | Ehema Dewal Na Hithe       | Modern Pop Music   |
| S08        | Kaari Naa Sanda            | Modern Pop Music   |
| S09        | Kaluwarata Hitha Baya      | Modern Pop Music   |
| S10        | Komaliya                   | Pop Music          |
| S11        | Ma Sadata Kamathi Bawa     | Classic Pop Music  |
| S12        | Mohini                     | Hip-hop            |
| S13        | Nuraavi                    | Modern Pop Music   |
| S14        | Perawadanak                | Classic Pop Music  |
| S15        | Piyanani                   | Pop Music          |
| S16        | Salli Salli                | Hip-hop            |
| S17        | Saragaye                   | Pop Music          |
| S18        | Sobana                     | Classic Pop Music  |
| S19        | Thaniwennata Mage Lowe     | Classic Pop Music  |
| S20        | Unmada Prema Geeya         | R&B            |



