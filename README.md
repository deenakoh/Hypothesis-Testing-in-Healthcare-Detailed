The dataset drug_safety.csv was obtained from Hbiostat courtesy of the Vanderbilt University Department of Biostatistics. It contained five adverse effects: headache, abdominal pain, dyspepsia, upper respiratory infection, chronic obstructive airway disease (COAD), demographic data, vital signs, lab measures, etc. The ratio of drug observations to placebo observations is 2 to 1.

For this project, the dataset has been modified to reflect the presence and absence of adverse effects adverse_effects and the number of adverse effects in a single individual num_effects.

The goal is to know if the adverse reactions, if any, are of significant proportions.

The columns in the modified dataset are:

Column Description:

sex - The gender of the individual age - The age of the individual week - The week of the drug testing trx - The treatment (Drug) and control (Placebo) groups wbc - The count of white blood cells rbc - The count of red blood cells adverse_effects - The presence of at least a single adverse effect num_effects - The number of adverse effects experienced by a single individual
