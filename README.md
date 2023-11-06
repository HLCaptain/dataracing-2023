# Loan prediction via Machine Learning

This is the machine learning model training code for the [Dataracing Challange 2023](https://eval.dataracing.hu/web/challenges/challenge-page/5/overview) competition.

## Installation

Install all the dependencies required by the jupyter notebook.

Download the dataset from [here](https://drive.google.com/drive/folders/1xPFJ_Ln0lo12oJZk7GN03e_vvCl8R6m9?usp=sharing). The zip is protected with a password, found on the [competition's website](https://eval.dataracing.hu/web/challenges/challenge-page/5/overview).

Content of the zip package:

- `training_data.csv` - training data
- `data_submission_example.csv` - sample solution, sample format of the data to be submitted

These files should be placed into the `data` folder.

## Usage

You can train models on the dataset by running the `loan_prediction.ipynb` notebook in Google Colab or locally.

After training, the best model is selected to predict data. The predicted data should be `predictions.csv` in the `data` folder, similar to `data_submission_example.csv`.

Models are put into the `models` folder.

Best models are places inside the `models/best` folder.

## License

[MIT](https://choosealicense.com/licenses/mit/)
