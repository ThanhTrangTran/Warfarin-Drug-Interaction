# Warfarin-Drug-Interaction
Detailed analysis of drug interactions with warfarin using synthetic data that is based on real pharmacy data from a large medical center.

## About the project:
During a pharmacy rotation at a large medical center, I was asked by the clinical pharmacy manager to determine the drugs that were interacting with warfarin and causing dangerous INR increases in patients which could potentially lead to fatal bleeding if not corrected promptly.

## About the dataset:
The dataset is data that I created which mimics the hospital pharmacy data that I had used during my rotation. The dataset provides information on admission and discharge dates, date and time of first warfarin dose given and when INR was first elevated, and the INR before warfarin administration and when elevated.

## Questions:
  1. What drugs were patients given that interacted with warfarin and caused an increase in their INR?
  2. How many drugs were patients on that could lead to a drug interaction?
  3. What specific antidote was needed most often?
  4. What steps should pharmacists take to ensure warfarin interactions do not become dangerous?
  
## Key takeaways (Answers to questions 1-3):
  1. 88% of patients with increased INR had recieved at least one drug that is known to interact with warfarin and cause an elevated INR.
  2. Amiodarone, an antiarrhythmic drug, was involved in nearly 30% of the elevated INR cases.
  3. Vitamin K 1 mg oral form was the most commonly used antidote in the warfarin drug interaction.
  
## Recommendations (Answer to question 4):
Pharmacists will need to monitor patients on warfarin and amiodarone carefully. If amiodarone is initiated in the hospital, warfarin dose should be decreased by 30-50%. Monitor for signs and symptoms of bleeding or an acute drop in hemoglobin (> 2g/dL). A larger supply of oral vitamin K 1 mg should be kept in the pharmacy.

## Tools used during analysis:
  1. Excel basic formulas (Calculations, COUNTIF, DATEDIF)
  2. Custom formulas derived from basic formulas (UNIQUE and TOCOL to create drug list [https://www.loom.com/share/cdf5d09f589f45a3a5eb1fc10c81461d])
