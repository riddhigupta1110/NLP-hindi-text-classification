# NLP-hindi-text-classification
Hindi Text Classification Project is a multi-label classification system designed to classify Hindi news articles into relevant categories using ML techniques. This project uses Logistic Regression and Naive Bayes models, with TF-IDF Vectorization for feature extraction, to process Hindi textual data.

## Notebooks:
1. **Hindi_Text_Classification.ipynb**  
   - Notebook for preprocessing, model training, and saving trained models (`.joblib` files).
2. **NLPGUI.ipynb**  
   - Notebook for launching a Gradio-based interactive User Interface (UI) for real-time predictions using saved models.

## Dataset:
Inshorts Dataset - Hindi News available at [Kaggle](https://www.kaggle.com/datasets/shivamtaneja2304/inshorts-dataset-hindi)

## How to Use:

### **1. Clone the Repository**
Download the repository to your local system or Colab environment:

```bash
https://github.com/riddhigupta1110/NLP-hindi-text-classification.git
```

### **2. Open the Notebooks**

Use Google Colab or Jupyter Notebook to open the notebooks:
1. Hindi_Text_Classification.ipynb for training and saving models.
2. NLPGUI.ipynb for launching the UI.

### **3. Download Pre-trained Models**

The pre-trained models are available in the repository. You need to download them and save them into the `/content/` directory in Google Colab:
1. logistic_regression_model.joblib
2. naive_bayes_model.joblib
3. tfidf_vectorizer.joblib
4. multi_label_binarizer.joblib

### **4. Launch the Gradio UI**

Once the models are downloaded, run the NLPGUI.ipynb notebook to start the interface.

Input a news headline and content.
The predictions for the categories will be displayed.

