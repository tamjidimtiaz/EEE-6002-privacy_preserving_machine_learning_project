# classification-QSAR-models-for-the-discrimination-of-very-toxic-and-not-very-toxic-molecules

In this framework, new Quantitative Structure-Activity Relationship (QSAR) models for the prediction of
very toxic (LD50 lower than 50 mg/kg) and nontoxic (LD50 greater than or equal to 2,000 mg/kg) endpoints
were developed, as described in this study. A Logistic Regression model is developed on a large set of
chemicals (8992), provided by the project coordinators, considering the five OCED principles for QSAR
applicability to regulatory endpoints. After implementation of the developed model, the model performance
is evaluated and the effect of different hyper-parameters is investigated by seven different graphical analysis.

## Dataset Description:

NICEATM and NCCT collected and curated a rat acute oral toxicity database of systemic toxicity Lethal Dose 50 (LD50) values, which represent the concentration needed to cause lethality in 50% of the utilized
animals. A total of five different modelling endpoints related to acute oral systemic toxicity were provided, on the basis of regulatory criteria and decision contexts used by ICCVAM agencies. In this study, two endpoints
were considered to calibrate qualitative QSAR models: a) very toxic (VT), defining molecules as positive (very toxic) if their experimental LD50 was lower than 50 mg/kg; b) non-toxic (NT), defining molecules
positive (nontoxic) if their experimental LD50 was greater than or equal to 2,000 mg/kg. When chemicals were associated to multiple experimental LD50values, the median of the lower quantile was computed to
report a single LD50 value. For the purpose of class identification for test LD50 values on the limit of hazard categories, any experimental value associated to a greater than (>) or less than (<) symbol was adjusted,
that is, >2,000 mg/kg was retained as 2,001 mg/kg and<2,000 mg/kg was retained as 1,999 mg/kg. This dataset provided 741 toxic/positive molecules and 8251 not very toxic/negative molecules.
Binary extended connectivity fingerprints were used as molecular descriptors for model calibration. Fingerprints(FPs) allow the complete representation of the molecular structural fragments in a series of binary
digits (bits)encoding the presence or absence (as 1 and 0, respectively)of particular fragments and substructures in the molecule.[5]There are several different algorithms for the calculation of binary FPs; among
them, the most frequently used hashing algorithms produce compact FPs but with a “collision” of multiple molecular fragments in the same bit(s), and a consequent loss of one-to-one correspondence with molecular
fragments.

