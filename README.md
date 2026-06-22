# Bookarang_3

Distilling recurring patterns in summaries

## Dataset

The dataset used in this project is **not included** in this repository because it contains proprietary and potentially sensitive information.

To run the analysis, place a tab-separated values (`.tsv`) file named `dataset_cleaned.tsv` in the project root directory. The dataset should contain at least the following columns:

| Column             | Description                                            |
| ------------------ | ------------------------------------------------------ |
| `automatic_output` | AI-generated book summary.                             |
| `final_edit`       | Human-edited version of the summary.                   |
| `genres`           | One or more book genres.                               |
| `VJ`               | Target audience category (e.g. adult, children, both). |
| `FNF`              | Fiction/non-fiction category.                          |

Additional metadata columns may be present but are not required for the notebook.

The notebook assumes this file structure and column naming throughout the analysis.
