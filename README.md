# task_word_explainability recreation by Shimon Islam

Code based on: S Agarwal, YR Semenov, W Lotter. Representing visual classification as a linear combination of words. _Proceedings of the 3rd Machine Learning for Health symposium, PMLR_ (2023).

## Set-up/Requirements
1. Download Kaggle Dataset for CBIS-DDSM and move both folders into a folder called 'data' within the project. Download here: https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset/data
2. Install CLIP and its dependencies by following instructions at: https://github.com/openai/CLIP
3. Install packages in `requirements.txt` in order to run all scripts. The code should generally be version agnostic for these packages. Run 'pip install -r requirements.txt' in the base folder.
4. Run training script using '{path to python} {path to script}' i.e. '/usr/local/bin/python /Users/username/task_word_explainability-main/fit_words.py' for Mac
5. Run graph generation script using '{path to python} {path to script}' i.e. '/usr/local/bin/python /Users/username/task_word_explainability-main/plotting.py' for Mac
6. Outputs of results will be in '/results' folder.

## Usage
`fit_words.py`: Illustrates fitting a linear classifier based on CLIP image embeddings and subquently estimating the classifier based on a linear combination of word embeddings.

`plotting.py`: Plots the regression word weights.
