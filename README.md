# A-DATA001 — Data/Analytics working package

## Included
- `Advenced-A-DATA001-DATA-SCIENCE`: original assignment structure, completed runnable code and charts.
- `48474967_Garza_Inc_and_Sons.csv`: supplied sample dataset (24 months).
- `requirements.txt`: Python dependencies.
- `VIDEO`

## Run
1. Open the folder in Jupyter Notebook, JupyterLab, or VS Code with Jupyter extension.
2. If required, install packages using `python -m pip install -r requirements.txt`.
3. Choose Python kernel; select **Restart & Run All**.
4. Read each assignment prompt and write your **own** observations/reflections in the markdown answer cells.
5. Create your **own** approx. two-minute 480p video, explaining your results to nontechnical colleagues.


Technical cautions:
- Payroll validation and test sets have **one observation each**, so MAE is not a robust accuracy estimate.
- Forecast error bands are illustrative historical error ranges, **not calibrated prediction intervals**.
- Revenue model comparison uses held-out data in the original dollar scale (not incomparable transformed MAEs).
- Negative-media classes are almost perfectly aligned with time; an apparently perfect six-record holdout score is **not** evidence of good future classification.
- Logistic model future inputs use month-36 log10 forecast revenue and assume scandals = 0.
