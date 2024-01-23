# <p align="center"><b>Age and gender prediction</b></p>

## **About project**
Our project is built to predict the gender and age of humans. The user’s gender and age are very important for organizations to understand their customers’ needs and develop their strategies to provide more enhanced services to them.

\- Input: Images containing the user's face. We use UTKFace dataset <br>
\- Output: <br>
\+ Age: A range representing an estimate of the person's age in the image: 8 age classes as “0–2,” “4–6,” “8–13,” “15–20,” “25–32,” “38–43,” “48–53,” and “60+” <br>
\+ Gender: Male or Female.<br>

## **Proposed work**
- Preprocessing: image processing chores include noise subdual, contrast enrichments, and removal of undesirable effects on detention such as blurring by motion effects and color alterations.
- DCNN is utilized for feature extraction, which learns relevant characteristics by retrieving distinctive features
- SVM classifies age and gender
- Evaluation: Confusion Matrix
- The model is robust and surpasses the conventional scheme in contexts of classification rate, precision, and recall, as demonstrated by experiments on the UTKFace dataset 

