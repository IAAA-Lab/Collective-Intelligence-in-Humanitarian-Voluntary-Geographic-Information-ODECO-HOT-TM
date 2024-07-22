# Collective-Intelligence-in-Humanitarian-Voluntary-Geographic-Information-ODECO-HOT-TM
This repository contains Python and R notebooks for the analysis of data from the Humanitarian OpenStreetMap Team Tasking Manager (HOT-TM) API.

* 0_Project_profiling.ipynb: this notebook describes the general attributes of the 746 analyzed projects: difficulty, priority, number of tasks, number of contributors, location of the projects and organizations.

* 1_Contributor_profiling.ipynb: this notebook describes the attributes of the contributors of the HOT projects analyzed: completeness of attributes, mapping level and location according to reported country.

* 3 Process_Analysis.Rmd: this notebook analyzes the mapping process using the BupaR library: control flow, duration and resources.

* 4_Collective_action.ipynb: this notebook analyzes the behavior of tasks that reported the intervention of more than one mapper.

* 5_Dataset_for_regression.ipynb: cleaning notebook to generate a dataset for a logistic regression where the dependent variable is the final state of the mapping, Validated (0) - Invalidated (1)

* 6 Logistic Regression.Rmd: This notebook performs a regression to determine the attributes of a task that make it most likely to be invalidated.
