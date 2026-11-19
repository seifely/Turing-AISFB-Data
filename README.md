# Turing-AISFB-Data
Unofficial workable Python data for the Turing Institute's AI Skills for Business Framework (V3.0.0) mapping Duties to Competencies to Skills.
Does not currently contain data on the personas, proficiency levels, lifecycle stages, knowledge statements or behaviour statements (only skill statements for now). 

Original work credited to:
_Forshaw, Matthew, Clementina Ramirez, Tahira Suleman, and Vera Matser. "A National Competency Framework for AI Skills across Education and the Workforce." In Proceedings of the 31st ACM Conference on Innovation and Technology in Computer Science Education V. 1, pp. 408-414. 2026._
Found at [this link](https://doi.org/10.5281/zenodo.18892559).

Contents primarily include a pickled dictionary containing:

* A list of duty-competency pairs, a list of competency-skill pairs
* Lists of unique codes within duties, competencies and skills
* A dict of duties, competencies and skills indexed by their code values, with each entry containing the item code and the item description
* Two dataframes, one for duty-competency entries and one for competency-skill entries
* Nested dictionaries in the format (Duty: [Duty Code, Duty Desc, Competencies: [Competency Code, Competency Desc, Skills: [Skill codes, Skills descs]]]
