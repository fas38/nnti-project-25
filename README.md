# Packages
All the packages used are added into the requirements.txt file.

# Task-1 (Fine Tuning LLM)
Task 1 is completed [here](./notebooks/Task1.ipynb). 

# Task-2 (Computing Influence Scores for all the Training Data Points)
Task 2 is completed in [here](./task_02.ipynb)

# Task-3 (Implementing Parameter Efficient Fine-Tuning and Data Selection Methods)
To apply the ts-shapley data selection method -  [TS-DShapley](./task_03.ipynb)


We have implemented three parameter efficient fine tuning methods - BitFit, LoRA, IA3. The following notebooks contain implementation and results for all the fine tuning methods for different data selection approaches - 

- [With No Data Selection](./Task3_all_data_points_Finetuning_Full_bitfit_Lora.ipynb)
- [Top 100 Influential Points Selected](./Task3_influential_top100_data_points_Finetuning_Full_bitfit_Lora.ipynb)
- [All Positive Influential Points Selected](./Task3_influential_data_points_Finetuning_Full_bitfit_Lora.ipynb)
- [TS-DShapley Selected Points](./Task3_shapley_selected_data_points_Finetuning_Full_bitfit_Lora.ipynb)

# Report
An overview of the implemented tasks and the results achieved can be found in - [report](./report_clean.pdf) and [slide](./NNTI%20project%20presentation-clean.pdf)