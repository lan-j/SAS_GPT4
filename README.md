# SAS_GPT4
Implementation of short answer scoring with GPT-4.

GPT_inference.ipynb contains the script for student answer scoring. 

Before running anything, be sure to adjust the following variables as necessary. "question" refers to the name of the dataset, "model" refers to the GPT model that will be called, and "exp_name" refers to the experiment to be conducted. All prompts used for experiments are under the folder "prompt", experiment name should be selected from [base(score_rationale_onequery), add_possible_answers, add_scored_examples, add_both, score_only, rationale_score_twoqueries, rationale_score_onequery], which corresponds to the experiment names in the paper.

question = 'Q1'
model = 'gpt-4-1106-preview'
exp_name = 'rationale_score_onequery'
