This challenge was proposed in the scope of an assigment regarding machine learning-based data analysis of the 
curricular unit “Intelligent Systems for Bioinformatics” integrated in the Bioinformatics Master Degree at University 
of Minho, 2022-2023. The code was developed by Group 6 composed of:
* Ana Camila Babo;
* Tomás Carreiró e Sá;
* José Diogo Moura.

The challenge was part of a Kaggle competition with the goal to predict the thermostability of enzyme variants 
through the use of natural and engineered sequences with single or multiple mutations whose thermostability was 
experimentally measured. More information regarding this topic can be obtained in notebook present in the src path.

## Repository Content

The present repository is organized in the following way:

- data_files/
    - data_distribution_plots/
      - aa_freq_distribution.png
      - enzyme_tm_class.png
      - feature_corr_plot.png
      - hydrophobic_distribution.png
      - length_distribution.png
      - ph_distribution.png
      - ppi_distribution.png
      - tm_distribution.png
    - fixed_train_df.csv
    - test.csv
    - train.csv
    - train_updates_20220920.csv
    - README.md
- src/
    - machine_learning_pipeline.ipynb
- .gitattributes
- .gitignore
- README.md
- LICENSE

The data_files directory contains all resources content regarding used datasets and obtained plots. 
Whereas the src directory contains the Machine Learning pipeline built for this project. 

