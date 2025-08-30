# Hospital Readmission Analysis — Novartis Administration Department
## Objectives
To analyze hospital admission and discharge data to:
- Identify patterns and risk factors associated with high readmission rates
- Quantify the impact of clinical, demographic, and procedural variables
- Recommend data-driven strategies to reduce preventable readmissions

## Dataset used
https://www.kaggle.com/datasets/shivavashishtha/hospital-administration-data/

## Key findings
Age distribution of encounters totals 13,392, with the largest buckets at 

The simple Pearson between number of emergencies and readmission rate is 0.1078, suggesting a weak positive relationship with readmission. 

The correlation between num_procedures and readmitted is −0.0443, indicating virtually no linear association in this sample. 

By procedure count, encounter volumes are: 0=6,787; 1=2,772; 2=1,516; 3=1,036; 4=475; 5=326; 6=480; total=13,392, showing most encounters involve zero or one recorded procedure. 

For diabetes-medication status, the average of readmitted is 0.4959 when Change=Yes and 0.4758 when No Change, a modest difference that suggests slightly higher readmission where medication changed. 
