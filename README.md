# PHI-Deidentification
De-identifying protected health information (PHI) from the Synthetic patient database

---

### Objective
The objective of this assignment was to implement the de-identification of protected health information (PHI) using tables from the Synthetic patient database. The goal was to create a de-identified patient lookup table for further analysis while adhering to Privacy Rules.

### Process
1. **Creation of Random Table**: A table named 'randomTable' was created with each patient ID connected to randomized values for date shift and ID number change.
2. **Fully De-identified Table**: PHI was de-identified to create a table named 'full_lookup', ensuring columns like 'medical_record_id', 'birthdate', 'deathdate', etc., were de-identified.
3. **Limited Data Set Table**: Another table named 'limit_lookup' was created with a limited dataset, containing only essential de-identified columns.
4. **Comparison of Unique Patients**: Validation was conducted to confirm that the de-identified tables contained the same patient data as the original.

### Results
- **Random Value Table Creation**: SQL queries were executed to create the 'randomTable' containing randomized values for date shift and ID number change.
- **Fully De-identified Table**: PHI columns were de-identified using various techniques such as date shifting, MD5 hashing, and randomization.
- **Limited Data Set Table**: A limited dataset table was created, containing only essential de-identified columns for analysis.
- **Validation of Equivalence**: Validation queries were executed to confirm that all de-identified tables contained the same patient data as the original dataset.

### Summary & Conclusion
In conclusion, this assignment successfully implemented the de-identification of PHI, ensuring compliance with HIPAA Privacy Rules. By creating fully de-identified and limited dataset tables, sensitive patient information was protected while still allowing for meaningful analysis. Validation checks confirmed the equivalence of de-identified tables with the original dataset, ensuring data integrity and privacy compliance.

---
