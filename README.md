# Family Size and Academic Performance of Female Secondary School Students

Statistical analysis of whether family size (`famsize`) is associated with the final Mathematics grade (`G3`) of female students in two Portuguese secondary schools, and whether free time (H1), extra educational resources (H2) or parental education (H3) explain or modify that association.

The full analysis is in [`main.ipynb`](main.ipynb): research question, data cleaning decisions, feature engineering, tests, conclusions and limitations.

## Main result

Students from large families score about 1.35 points lower on a 0–20 scale (p = 0.068). The difference is not statistically significant, and none of the three hypotheses was confirmed.

## Data

`student-mat.csv` comes from the UCI Student Performance dataset, also available on [Kaggle](https://www.kaggle.com/datasets/janiobachmann/math-students/data).

> P. Cortez and A. Silva. *Using Data Mining to Predict Secondary School Student Performance.* Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008), pp. 5–12, Porto, Portugal, 2008.

## How to run

```bash
pip install -r requirements.txt
jupyter notebook main.ipynb
```

Then run **Kernel → Restart & Run All**. The notebook expects `student-mat.csv` in the same folder and saves its figures (`*.png`) there too.
