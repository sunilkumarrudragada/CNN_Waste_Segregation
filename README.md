# Waste Segregation
> Waste Segregation By using CNNs


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem
- Improper waste disposal contributes to environmental degradation, increased landfill waste and inefficient recycling processes. Manual sorting is labour-intensive, error-prone and costly. An AI-powered waste classification system addresses these challenges by streamlining waste segregation, reducing operational costs and improving recycling rates.
### Dataset
- We are using the dataset which contains 7 folders, each one represents a category

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The dataset suffers from **class imbalance and limited samples** for certain categories, leading to biased learning toward dominant classes like Plastic.
- Initial models without regularization overfit quickly, showing a large gap between training and validation performance.
- Applying **data augmentation and regularization techniques** (Dropout, BatchNorm, L2) improved generalization and classification performance, especially for underrepresented classes like Glass and Paper.
- Further improvements can be achieved through **transfer learning** using pre-trained CNNs like ResNet or VGGNet to leverage powerful, general-purpose feature extractors.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
| Library        | Version   |
|----------------|-----------|
| numpy          | 2.0.2     |
| pandas         | 2.2.2     |
| matplotlib     | 3.10.0    |
| seaborn        | 0.13.2    |
| tensorflow     | 2.18.0    |
| scikit-learn   | 1.6.1     |
| Pillow (PIL)   | 11.2.1    |

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->