# AI for Medical Diagnosis - Learning Summary Week 1 Asignment

📊 **Data Preparation:**
   - Visualized medical image data to understand dataset characteristics.
   - Implemented techniques to prevent data leakage, ensuring model integrity
      - Splitting train, validation, and test set into patient IDs, to avoid the model picking up features that may not be related to a disease detection: eg. healthy patient wears a necklace in both x-ray scans in train and test set → model picks up “necklace” = healthy, which is false and makes the model overconfident. 

🚀 **Model Development:**
   - Addressed class imbalance for robust classifiers.
   - Leveraged transfer learning with pre-trained DenseNet models, accelerating training.

📈 **Evaluation:**
   - Utilized advanced metrics - AUC and ROC curves - for comprehensive model evaluation.
   - Gained insights into diagnostic performance, understanding sensitivity and specificity.

🔍 **Visualization:**
   - Explored GradCAMs to visualize model predictions.
   - Identified crucial regions of interest in chest X-ray images.

💻 **Implementation:**
   - Applied theoretical knowledge to practical scenarios.
   - Developed skills in data preprocessing, model development, and advanced evaluation.
