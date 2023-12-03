## Decision Tree & Random Forest Classifier:

The Ionosphere Dataset from the UCI machine learning repository consists of a phased array of 16 high-frequency antennas with a total transmitted power on the order of 6.4 kilowatts. Received signals were processed using an autocorrelation function whose arguments are the time of a pulse and the pulse number. There were 17 pulse numbers for the system. Instances in this database are described by 2 attributes per pulse number, corresponding to the complex values returned by the function resulting from the complex electromagnetic signal. "Good" (g) radar returns are those showing evidence of some type of structure in the ionosphere. "Bad" (b) returns are those that do not; their signals pass through the ionosphere. This task involves binary classification, utilizing both the Decision Tree and Random Forest Classifier to assess their respective classification performances. A comparative analysis will be conducted to identify the superior performer, considering factors such as Confusion Matrix, Sensitivity, Specificity, Total Accuracy, F1-score, ROC, and AUC scores. Additionally, 5-Fold cross-validation will be applied to evaluate the models' overall effectiveness.

**Important Note:** 5-fold cross-validation is a method in machine learning where the dataset is divided into five subsets, and the model is trained and tested five times using different combinations of training and testing sets to obtain a more robust evaluation of its performance.

## 🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn.

Sublime Text: Efficient, versatile code editor with minimalist interface.

## 📈 Results:

**Decision Tree (Entropy)**
* The Decision Tree classifier, employing entropy as its criterion, demonstrated strong predictive performance on the UCI machine learning ionosphere dataset. Notably, it achieved a sensitivity of 85.3% and specificity of 93.8%, resulting in an overall model accuracy of 90.5%. The precision rate reached 89.7%, indicating the reliability of positive predictions, and the F1 score was impressive at 91.7%, reflecting a balanced trade-off between precision and recall.
  
**Random Forest**
* The Random Forest classifier exhibited exceptional performance when applied to the UCI machine learning ionosphere dataset. With a sensitivity of 97.2%, the model demonstrated a remarkable ability to accurately identify positive instances (ionosphere occurrences), while maintaining a specificity of 94.2% for precise identification of negative instances. The overall model accuracy reached an impressive 95.2%, indicating the model's proficiency in correctly classifying both positive and negative cases. Furthermore, the F1 score, reflecting a balanced trade-off between precision and recall, stood at 91.9%, underscoring the model's reliability and effectiveness in binary classification tasks.

**5-Fold Decision Tree (Entropy)**
* The Decision Tree classifier, utilizing entropy as its criterion and evaluated through 5-fold cross-validation on the UCI machine learning ionosphere dataset, demonstrated varying accuracy scores across different folds. The accuracy scores were observed as 77.4%, 87.1%, 87.1%, 85.7%, and 91.4%, indicating fluctuating performance levels across the subsets. While the model exhibited lower accuracy in some folds, the higher scores suggest its effectiveness in accurately classifying instances in the ionosphere dataset, highlighting the importance of cross-validation for a comprehensive assessment of its predictive capabilities.

**5-Fold Random Forest**
* The Random Forest classifier, assessed through 5-fold cross-validation on the UCI machine learning ionosphere dataset, demonstrated consistent and high accuracy scores across different folds. The accuracy scores were notably strong, ranging from 92.9% to 100%, with individual scores of 88.5%, 90%, and 95.7%. These findings suggest the robustness of the Random Forest model in accurately predicting outcomes for the ionosphere dataset. The high and consistent accuracy scores across folds underscore the model's reliability and effectiveness in handling variations within the dataset.

**ROC & AUC**
* The ROC and AUC analyses were conducted to assess the performance of the Decision Tree and Random Forest classifiers. In comparison, the Random Forest classifier displayed exceptional discriminative ability with a perfect AUC score of 1.00, indicating flawless separation between the positive and negative classes. On the other hand, the Decision Tree classifier yielded a respectable AUC score of 0.90. Although not perfect, this score still suggests good discriminative power, with the model effectively distinguishing between positive and negative instances. In summary, the Random Forest's AUC of 1.00 signifies outstanding performance and near-perfect separation of classes, while the Decision Tree's AUC of 0.90 indicates strong discriminative ability.

**Overall**
* Considering the overall performance metrics and the 5-fold cross-validation accuracy scores of both models, the Random Forest model appears to have performed better in terms of overall accuracy and sensitivity. It consistently achieved high accuracy across different folds, and its sensitivity (97.2%) is notably higher than that of the Decision Tree model (85.3%). Random Forests, known for often outperforming individual Decision Trees by mitigating overfitting and improving generalization, demonstrated a robust ability to accurately classify instances, especially positive cases (good "g"), as reflected in its high sensitivity.

## 🔗 How to Use:

Each project/code along with their dataset has been uploaded for your review or observation. Please feel free to reach out if you have questions, suggestions, or if you're interested in collaboration!

## 🌐 Connect with Me:

LinkedIn: (https://www.linkedin.com/in/faridatlawal/)

##### I'm continuously learning and expanding my skill set. Join me on this exciting journey through the world of machine learning! 🤖✨
