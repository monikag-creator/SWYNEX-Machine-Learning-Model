# SWYNEX-Machine-Learning-Model
# SWYNEX Machine Learning Model — Task 2

Internship task for SWYNEX Technologies: train and evaluate ML models.

## Dataset
PlantVillage (38 plant disease classes)

## Models Trained
- SVM (RBF kernel)
- CNN (3 convolutional layers)

## Results
| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| SVM | 0.626 | 0.627 | 0.626 | 0.622 |
| CNN | 0.887 | 0.897 | 0.887 | 0.888 |

## Conclusion
The CNN significantly outperformed SVM (88.7% vs 62.6% accuracy) because it 
learns spatial features (edges, shapes, textures) directly from images through 
convolutional filters, while SVM relies on flattened pixel values that lose 
this spatial structure.
