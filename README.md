# TrashNet Classifier

Fine‑tunes a ResNet18 CNN to classify six types of household waste using the TrashNet dataset.

## 🚀 Features

* Preprocesses and augments 2,520 labeled images (resizing, normalization, random flips)
* Fine‑tunes a pre‑trained ResNet18 in PyTorch for multiclass waste classification
* Evaluates model performance with per‑class precision, recall, F1‑score, and overall accuracy

## 🛠️ Tech Stack

* **Framework:** PyTorch, torchvision
* **Libraries:** NumPy, scikit‑learn, Matplotlib


## 📈 Performance

| Class     | Precision | Recall | F1‑Score |
| --------- | --------- | ------ | -------- |
| Cardboard | 0.92      | 0.91   | 0.91     |
| Glass     | 0.94      | 0.93   | 0.94     |
| Metal     | 0.90      | 0.89   | 0.89     |
| Paper     | 0.93      | 0.95   | 0.94     |
| Plastic   | 0.89      | 0.90   | 0.89     |
| Trash     | 0.88      | 0.87   | 0.87     |

