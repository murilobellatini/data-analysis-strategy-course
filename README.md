# Data Analysis Strategies: solved notebooks

English · [Português](README.pt-BR.md)

Solved notebooks for my course *Data Analysis Strategies*.
One case, the Titanic: who survived, and why.
From loading the data to correlations, one hypothesis at a time.

Tools: Python, pandas, NumPy, Seaborn, Matplotlib.

| # | Lesson | Open in Colab | Video (Portuguese) |
|---|--------|---------------|------------|
| 1 | Loading and Exporting Data (IO) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/01-data-loading-and-export.ipynb) | [Video](https://youtu.be/-VCBHyRXCAI) |
| 2 | Data Quality and Variable Types | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/02-data-quality-and-variable-types.ipynb) | [Video](https://youtu.be/KZVLXqGNlx4) |
| 3 | Hypothesis: The Fancy Guess | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/03-hypothesis-the-fancy-guess.ipynb) | [Video](https://youtu.be/7WtAiDxaMJM) |
| 4 | Mapping Hypotheses | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/04-mapping-hypotheses.ipynb) | [Video](https://youtu.be/Ao0KNE-b5Ow) |
| 5 | Analyzing Categorical Variables | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/05-categorical-variables.ipynb) | [Video](https://youtu.be/_XiRhikPX8w) |
| 6 | Analyzing Numerical Variables | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/06-numerical-variables.ipynb) | [Video](https://youtu.be/gansSWE75RE) |
| 7 | Analyzing Text and Feature Engineering | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/07-text-and-feature-engineering.ipynb) | [Video](https://youtu.be/HQig5uwL-7k) |
| 8 | Segmenting Numerical Data | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/08-segmenting-numerical-data.ipynb) |  |
| 9 | Being Consistent | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/09-being-consistent.ipynb) |  |
| 10 | Analyzing Proportions | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/10-proportions.ipynb) |  |
| 11 | Analyzing Correlations | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilobellatini/data-analysis-strategy-course/blob/main/en/11-correlations.ipynb) |  |

- Folder `pt/`: the original notebooks, in Portuguese. No saved outputs: run them to see the charts.
- Folder `en/`: the same notebooks in English. The code is the same, only the text and comments change.
- Free pandas cheat sheet (PDF, English and Portuguese): https://muriloapps.dpdns.org/downloads/
- The course videos are separate and spoken in Portuguese. An English version comes later.

### Work with Claude Code

Learn with an AI helper that knows this course.

1. Install Claude Code (macOS, Linux, WSL): `curl -fsSL https://claude.ai/install.sh | bash`. Other systems: https://code.claude.com/docs/en/quickstart
2. Get the course: `git clone https://github.com/murilobellatini/data-analysis-strategy-course.git`
3. Go into the folder: `cd data-analysis-strategy-course`
4. Start it: `claude`
5. Add the skills, inside Claude Code:
   - `/plugin marketplace add murilobellatini/agent-skills`
   - `/plugin install data-analysis-skills@murilo-agent-skills`
6. Try a first prompt: `use pandas-explore on the Titanic data`

The `CLAUDE.md` file in this folder tells Claude how the course works.

### Data

The notebooks download Titanic (`train.csv`, `test.csv`) from `github.com/murilobellatini/datasets`.
I did not copy the files here. The original data is on Kaggle: https://www.kaggle.com/c/titanic

### Licence

Code under the MIT licence (see `LICENSE`).
