GUIDE QUESTIONS (Student Explanation & Reflection)

A. Model Evaluation Analysis

1. What were the weakest-performing classes based on the confusion matrix?
Answer. The weakest classes were the ones with the most wrong predictions in the confusion matrix (many misclassified images).

2. How did Precision, Recall, and F1-score vary across classes?
Answer. Some classes had high scores, but others were low. This means the model performed well on some classes but poorly on others.

3. What does a low recall indicate in your model?
Answer. Low recall means the model missed many actual images of that class (many false negatives).

4. How does AUC score reflect model performance compared to accuracy?
Answer. AUC shows how well the model separates classes, while accuracy only shows correct predictions. AUC is more reliable for overall performance.


B. Model Improvement

5. How did data augmentation affect validation accuracy?
Answer. It improved validation accuracy because the model saw more varied images and learned better.

6. Why is Batch Normalization important in CNNs?
Answer. It helps the model train faster and makes learning more stable.

7. What role did Dropout play in improving your model?
Answer. Dropout reduces overfitting by randomly turning off some neurons during training.

8. How did Early Stopping prevent overfitting?
nswer. It stops training when validation performance stops improving, preventing overfitting.

C. Performance Comparison

9. What improvements were observed after modifying the model?
Answer. Accuracy increased, loss decreased, and predictions became more correct.

10. Which enhancement contributed the most to performance improvement? Why?
Answer. Data augmentation helped the most because it improved generalization.

11. Did the gap between training and validation accuracy decrease? Explain.
Answer. Yes, the gap decreased, meaning the model became less overfitted and more balanced.

D. Explainability (Grad-CAM Integration)

12. How did Grad-CAM help in understanding model predictions?
Answer. It showed which parts of the image the model focused on when making predictions.

13. Did the improved model focus on more relevant regions? Provide evidence.
Answer. Yes, it focused more on important areas (like the main object), not the background.

14. Why is explainability important in real-world AI applications?
Answer. It helps people trust the model and understand its decisions in real-life use.
