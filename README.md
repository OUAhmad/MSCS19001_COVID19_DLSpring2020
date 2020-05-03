# MSCS19001_COVID19_DLSpring2020
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

### Dataset:
[Dataset Folder](https://drive.google.com/drive/u/3/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)<br>
[Dataset Zip file](https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view)<br>

### Results:

| Backbone | Frozen Layers| Epochs | Training Time | Training Set Accuracy/F1 Score | Validation Set Accuracy/F1 Score | Testing Set Accuracy/F1 Score |
|----------|----------------------|--------|---------------|-----------------------|-------------------------|-----------------------|
| VGG16    | All Layers except FC | 15     | <1hr          | 89/0.907              | 88/0.902                | 94/0.955              |
| VGG16    | First 7 CNN Layers   | 12     | =1hr          | 92/0.939              | 91/0.925                | 96/0.974              |
| VGG16    | First  CNN Layers    | 14     | =1hr 25min    | 93/0.942              | 90/0.924                | 96/0.971              |
| VGG16    | None                 | 11     | =1hr 40min    | 91/0.934              | 91/0.928                | 97/0.975              |
| RESNET18 | All Layers except FC | 15     | =1hr          | 83/0.855              | 79/0.811                | 86/0.875              |
| RESNET18 | None                 | 20     | =1hr 40min    | 88/0.911              | 91/0.927                | 96/0.970              |

## Covid19 Classification using Focal Loss

### Dataset:
[Dataset Zip file](https://drive.google.com/open?id=1kGnCJ8AFKgMoxhN1G3yFHXdFLWAbgY5K)

### Results:

| Backbone | Loss Function| Epochs | Training Time | Training Set Accuracy/F1 Score | Validation Set Accuracy/F1 Score |
|----------|----------------------|--------|---------------|-----------------------|-------------------------|
| VGG16    | BCE With Logits Loss | 15     | =1hr 10min    | 92/92                 | 93/93                   |
| VGG16    | Focal Loss           | 25     | =2hr 30 min   | 83/84                 | 89/90                   |
| RESNET18 | BCE With Logits Loss | 20     | =2 hours      | 92/91                 | 94/94                   |
| RESNET18 | Focal Loss           | 22     | =3 hours      | 87/87                 | 90/90                   |

