# MSCS19001_COVID19_DLSpring2020
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

## Dataset:
https://drive.google.com/file/u/3/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view?usp=drive_open

## Results:

| Model    | Frozen Layers        | Epochs | Training Time | Training Set Accuracy | Validation Set Accuracy | Testing Set Accuracy  |
|----------|----------------------|--------|---------------|-----------------------|-------------------------|-----------------------|
| VGG16    | All Layers except FC | 15     | <1hr          | 89                    | 88                      | 94                    |
| VGG16    | First 7 CNN Layers   | 12     | =1hr          | 92                    | 91                      | 96                    |
| VGG16    | First  CNN Layers    | 14     | =1hr 25min    | 93                    | 90                      | 96                    |
| VGG16    | None                 | 11     | =1hr 40min    | 91                    | 91                      |                       |
| RESNET18 | All Layers except FC | 15     | =1hr          | 83                    | 79                      | 86                    |
| RESNET18 | None                 | 20     | =1hr 40min    | 88                    | 91                      |           96          |
