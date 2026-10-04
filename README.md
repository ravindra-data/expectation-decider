# Expectation Decider

Probability analysis of 200 students to find what affects passing a competitive mathematics exam.

## About
This project uses probability concepts in Python (Jupyter Notebook) to study how study hours, attendance, group discussion and previous test score relate to passing the final exam. The dataset is synthetic (generated for this project).

## Dataset
`expectation_decider_dataset.csv` has 200 rows:

| Column | Description |
|---|---|
| student_id | Student ID |
| study_hours | Hours studied per week |
| attendance | Attendance percentage |
| group_discussion | Participates in group discussion (Yes/No) |
| previous_test_score | Marks out of 100 in the last test |
| final_exam_pass | Pass or Fail |

## Topics covered
1. Probability basics and events
2. Empirical vs theoretical probability
3. Random variable and probability distribution (mean, variance)
4. Venn diagram
5. Contingency table (joint, marginal, conditional probability)
6. Independent, dependent and mutually exclusive events
7. Bayes' theorem
8. Charts and final summary

## Key findings
- About 54.5% of students pass.
- Previous test score, study hours and attendance affect passing the most.
- P(Pass | Group discussion) = 62.7%, compared with 44.4% without it, so the events are dependent.
- Bayes' theorem: P(Pass | High attendance) = 77.8%.

## Files
- `Expectation_Decider.ipynb`: the analysis notebook
- `expectation_decider_dataset.csv`: the dataset

## How to run
```bash
pip install pandas matplotlib jupyter
jupyter notebook Expectation_Decider.ipynb
```
Keep the CSV file in the same folder as the notebook.

## Tools
Python, pandas, matplotlib, Jupyter Notebook
