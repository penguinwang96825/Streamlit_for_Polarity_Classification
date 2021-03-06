# Streamlit for Toxicity Classification
This is a demo illustrating a classification model using BERT on Google Play dataset. I did not train the BERT model with every apps' reviews on Google Play, instead, I used only a few apps' reviews to train on the model anyway. To put it succinctly, this BERT model can detect polarity across a diverse range of Japanese reviews.

## Step 1: Download Repository
Download repository:

1. `git clone git@github.com:penguinwang96825/Streamlit_for_Toxicity_Classification.git`
2. `cd Streamlit_for_Toxicity_Classification`

## Step 2: Download Pre-trained Model
Download [file](https://drive.google.com/file/d/1i79tQKYwzj_RZIrr0h34vRYSKJRl0p4L/view?usp=sharing) and put it into `Streamlit_for_Toxicity_Classification` folder.

## Step 3: Set up Environment
Download the `requirements.txt` file and run it in the terminal.

`pip install -r requirements.txt`

## Step 4: Run App
1. Run the demo in terminal: `streamlit run app.py`
2. View the Streamlit app in your browser: `http://localhost:8501`

![demo](https://github.com/penguinwang96825/Streamlit_for_Toxicity_Classification/blob/master/image/demo.png)

## © Copyright
See [License](https://github.com/penguinwang96825/Streamlit-for-Toxicity-Classification/blob/master/LICENSE) for more details.
