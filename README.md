# Beta-Preparing-to-Model
Kaggle dataset having to do with gene expression via DNA microarray with ALL/AML cancer 

What I want to do is to align the dataframes up by patient number.  The problem is that in the "train_df" dataframe,
the columns are misnumbered.  For example, column 1 is patient 1.  column 2 is patient 2. column 33 = patient 33.  The problem
is that the column numbers are not in numerical order.  What I want to do is put the column numbers in numerical order in the
train_df dataframe so that I can then somehow concatenate with the "act_df" dataframe because then I will have a master
dataframe that has the gene expression numbers per patient and whether the patient had ALL or AML type of leukemia.
DO you know of any way to do this?  I've tried researching this but haven't found a suitable answer.
