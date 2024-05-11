# SAS_GPT4
The script used for [Short answer scoring with GPT-4](https://doi.org/10.1145/3657604.3664685).

## How to run the code
`GPT_inference.ipynb` contains the script for student answer scoring. 

Before running anything, be sure to adjust the following variables as needed. All prompts used for experiments are under the folder `prompt/`

|     Variable              |             Description                           | Options                                               |
|---------------------------| ------------------------------------------------- |------------------------------------------------------ |
| `question`                | Name of the dataset                               | `Q1`                                                  |
| `model`                   | GPT model that will be called                     | [Models available by OpenAI API](https://platform.openai.com/docs/models/gpt-4-turbo-and-gpt-4)  |
| `exp_name`                | Experiment to be conducted (corresponds to the experiment names in the paper)      | `base(score_rationale_onequery)`, `add_possible_answers`, `add_scored_examples`, `add_both`, `score_only`, `rationale_score_twoqueries`, `rationale_score_onequery`                  |

## Citation

The paper will appear at L@S 2024. If you found this code useful please cite our work as:

```bibtex
@inproceedings{jiang2024sas,
    author = {Jiang, Lan and Bosch, Nigel},
    title = {Short answer scoring with GPT-4},
    booktitle = {L@S2024},
    year = {2024},
}
```
