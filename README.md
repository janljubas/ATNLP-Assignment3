This repository is related to Assignment 3 for the NDAK19001U: Advanced Topics in Natural Language Processing course held at University of Copenhagen.


In order to obtain experiment results, one must run the `ATNLP_Assignment3_finetuning.ipynb` file, block by block.
The notebook is organized into setup, data preparation, model training and evaluation.

It has been used incrementally for all the experiments (apart from the LoRA approach and some data visualization inside the `LoRA.ipynb` notebook);
in order to fully recreate all the results, one must choose to run the right code block.

For example, whether one wants to evaluate the model performance for Experiment 1 or Experiment 2, they need to use the appropriate evaluation function - one implements the oracle lengths information, while other one doesn't.

The same goes for using the right tokenizer (available inside the `data` directory and in the root), right training and the right testing data. All are available and sorted inside the `data` directory.

**It is also recommended in this stage (before potential future refactor) to run the notebook in Google Colab environment, as it was during development.**
