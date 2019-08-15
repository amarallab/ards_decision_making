# A quantitative approach for the analysis of clinician recognition of acute respiratory distress syndrome using electronic health record data

This is the public data repository for the paper “A quantitative approach for the analysis of clinician recognition of acute respiratory distress syndrome using electronic health record data”. All data are available in csv form with the following columns:

 * Bilat_bool: Boolean, whether the patient has bilateral infiltrates on chest imaging at any point during their ICU stay (note: all patients in the ARDS cohort will have bilateral infiltrates as it is a requirement of the Berlin Definition)
 * Documentation: Boolean, whether the patient has a documented diagnosis of ARDS in their chart at any point during their ICU stay
 * Height_in: height in inches, rounded to the first decimal place
 * ICU_admit_wt: weight in kg on admission to ICU
 * PBW: predicted body weight (kg) as calculated by the ARDSnet formula
 * Cohort: ARDS or control – which cohort the patient was assigned to during our application of the Berlin Definition
 * Gender: male (M) or female (F)
 * Lowest_PF: lowest P/F ratio at any point during a patient’s ICU stay
 * Lowest_vt_hat: lowest standardized tidal volume (mL/kg PBW) achieved during a patient’s ICU stay
 * Qual_PF_val: P/F ratio at entry into the study
 * ICU_DI: type of ICU that the patient was treated in

[data set](combined_data_for_public_repository.csv)
