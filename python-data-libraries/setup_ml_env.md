### VS Code Extensions You Need
You already have:  
- Python  
- Jupyter  
Also install these:
| Extension      | Why                                           |
|---------------|-----------------------------------------------|
| Pylance       | Smart code completions & error detection      |
| Python Indent | Auto-fixes indentation (saves headaches!)     |
| GitLens       | Git tracking — essential for ML projects & portfolio |
| Rainbow CSV   | View CSV files nicely in VS Code              |
| Excel Viewer  | Preview Excel files directly in VS Code       |
### All Libraries — Install at Once
Open your VS Code Terminal and run this single command:
```bash
pip install pandas numpy matplotlib scikit-learn seaborn scipy jupyter notebook ipykernel flask requests openpyxlWhat Each Library Does
| Library      | Purpose                          | When You'll Use It                     |
|-------------|-----------------------------------|----------------------------------------|
| pandas      | Data manipulation & analysis      | Every single ML project                |
| numpy       | Numerical computing & arrays      | Foundation of all ML math              |
| matplotlib  | Basic data visualization          | Plotting graphs & charts               |
| seaborn     | Advanced beautiful visualizations | Built on matplotlib, much nicer graphs |
| scikit-learn| ML models & tools                 | Building, training, evaluating models  |
| scipy       | Scientific & statistical computing| Advanced math & statistics             |
| jupyter     | Jupyter notebooks                 | Interactive coding & learning          |
| notebook    | Jupyter notebook backend          | Required to run notebooks              |
| ipykernel   | Connect Python to Jupyter         | Makes Jupyter work inside VS Code      |
| flask       | Web framework                     | Deploying ML models as APIs            |
| requests    | HTTP requests                     | Calling APIs in ML pipelines           |
| openpyxl    | Read/write Excel files            | Loading .xlsx data into pandas         |


Verify Everything Installed Correctly
After installing, run this in your terminal:
bash
python -c "import pandas; import numpy; import matplotlib; import sklearn; import seaborn; print('All good!')"
If you see All good! — you're ready!
One More Thing — Folder Structure
Set up your workspace like this:
text
ml-learning/
├── 01_pandas/
│   └── <https://app.moveworks.ai/r?v2_ZkOG7Bm641zUAcaf|lesson1.ipynb>
├── 02_numpy/
├── 03_matplotlib/
├── 04_sklearn/
├── 05_projects/
└── data/