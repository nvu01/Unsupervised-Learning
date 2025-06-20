# Customer Segmentation Project

This project aims to identify customer segments for a mail-order company based on demographic data. The process involves data preprocessing, feature transformation, and clustering using techniques such as Principal Component Analysis (PCA) and K-means clustering.

## Steps Overview

**Step 1: Preprocessing**

In this step, I investigated the data to understand its structure and handle missing or unknown values. Key tasks include:
- Identifying and handling missing values. 
- Encoding categorical features. 
- Deciding which columns or rows should be removed or treated separately. 
- Determining which features need to be transformed for further analysis.

**Step 2: Feature Transformation**

Once the data is cleaned, I appied dimensionality reduction techniques to find relationships between variables and reduce the feature space:
- Feature Scaling: Scaling the features to ensure that all features contribute equally to the analysis. 
- Principal Component Analysis (PCA): Reducing the dimensionality of the dataset by identifying components with maximal variability and interpreting relationships between features.

**Step 3: Clustering**

In the final step, I applied clustering techniques to segment the data:
- K-means Clustering: I used K-means to group the general population data and apply the same model to the customer dataset. 
- I then compared the customer segments with the general population and analyze which segments are more likely to be consumers of the mail-order company.

## Dataset

The following datasets were used for the project, though they **will not be shared** as part of this submission:
- **Udacity_AZDIAS_Subset.csv**: Demographic data for the general population of Germany (891,211 persons x 85 features).
- **Udacity_CUSTOMERS_Subset.csv**: Demographic data for customers of a mail-order company (191,652 persons x 85 features).
- **Data_Dictionary.md**: Information about the features in the datasets.
- **AZDIAS_Feature_Summary.csv**: Summary of feature attributes for demographic data.

### Important Note:
Since the datasets are proprietary, **only the HTML version of the completed notebook** will be shared. The datasets are not included due to confidentiality agreements.