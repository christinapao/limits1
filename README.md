# Limits of Prediction - Course Assignment 1 
## (Anna Konvicka, Varun Satish, Christina Pao)

This repository has the data cleaning and data viz files to make the figures contained in our final writeup for the Course Assignment 1 (https://msalganik.github.io/soc555-cos598J_s2024/assignments.html).

The `plan_of_action.qmd` prints to the `plan_of_action.pdf` which contains information on what we did (in informal terms) for the replication and extension of the Hebre et al. papers. You'll see that we have csv's (`predictions_by_model.csv` and `real_prop_conflict.csv`) that we cleaned for clean versions of the data downloaded from the Hegre et al. replication files. The `model_iteration.ipynb` file uses the csvs that we created to then create loops of the different model combinations. This creates an output csv called `our_predictions_for_all_years.csv`. This then can be loaded in using `figures.qmd`, which produces the PDF `figures.pdf` (and the corresponding png files called `fig1.png` and `fig2.png`). These are the two figures that we use in our final writeup.
