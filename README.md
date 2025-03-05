# Machine Learning Intern Assessment Project

## Project Overview
In this 2 day assessment, you'll develop a model to classify product images into their respective categories. This project tests your computer vision skills, feature engineering approach, and model selection decisions.

## Dataset
We will be using a subset of the assessment dataset which contains:
- High-resolution product images 
- Multiple category labels per product
- Product descriptions and metadata
- A diverse range of product types
- The link to the dataset is [here](https://drive.google.com/file/d/1vWl0jXYcxNcNvSBNp8-53aJQkJE-3-fe/view?usp=sharing)

For this assessment:
- You will work with a subset of 1,500 images across 5 selected categories
- Data is split into training set (70%) with labels and test set (30%) without labels
- The dataset includes styles.csv (product metadata) and corresponding image files
- The use of Pytorch is mandatory

## Project Requirements

### Part 1: Exploratory Data Analysis 
- Examine the image dataset distribution and characteristics
- Analyze image sizes, color distributions, and other relevant properties
- Create at least two visualizations showing differences between categories
- Document your observations in markdown cells

### Part 2: Feature Engineering 
- Extract meaningful features from the product images beyond raw pixels
- Implement at least two different feature extraction techniques:
  * Traditional CV features (HOG, SIFT, color histograms, etc.)
  * Deep learning features (using pre-trained models)
  * Custom features based on fashion/product domain knowledge
- Optional: Explore using the product metadata (from styles.csv) as additional features
- Document your feature engineering decisions and implementation

### Part 3: Model Development
- Implement and compare at least three different classification approaches
- Options include:
  * Train a classifier on your engineered features
  * Fine-tune a pre-trained CNN
  * Implement transfer learning with a customized approach
  * Implement a semi-supervised learning approach
- Evaluate models using appropriate metrics (accuracy, precision, recall, F1-score)
- Create a confusion matrix visualization for your best model

### Part 4: Analysis & Reflection 
- Analyze which types of images your model handles well vs. poorly
- Identify specific challenges in the dataset
- Discuss what you would improve with more time
- Submit predictions for the test set

## Submission Requirements
1. Jupyter notebook with your complete solution
2. Code should be well-commented and follow PEP 8 style guidelines
3. Include markdown cells explaining your approach at each stage
4. CSV file with predictions for the test set

## Assessment Criteria
1. **Feature extraction creativity:** Quality and effectiveness of image features
2. **Technical implementation:** Code quality and execution
3. **Analysis depth:** Thoroughness of your data exploration and results analysis
4. **Model performance:** Accuracy and other relevant metrics on the test set
5. **Communication:** Clarity of documentation and explanations

## Dataset Source
The dataset is a curated dataset, which contains product images with multiple category labels, descriptions, and metadata. The full dataset includes professionally shot high-resolution product images along with descriptive attributes.

For this assessment, we've selected 1,500 representative images across 5 major product categories. You'll have access to:
1. Product images (.jpg files)
2. A subset of styles.csv with relevant metadata
3. JSON files containing additional product information

You will receive access to the dataset when you begin the assessment.

## Environment Setup
We recommend using Google Colab or a similar environment with GPU support for this project.

## Questions
If you have any questions about the project requirements, please contact [Anirudh.kalia@secnd.ca].
