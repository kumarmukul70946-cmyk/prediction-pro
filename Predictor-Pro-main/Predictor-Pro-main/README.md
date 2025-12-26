# Predictor-Pro

Simple Streamlit stock price prediction app using yfinance and Prophet.

## Run locally

1. (Optional) Create a virtual environment or conda env.

PowerShell venv:
```powershell
Set-Location -Path "C:\Users\Mukul Anand\Downloads\Predictor-Pro-main\Predictor-Pro-main\prediction pro"
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
python -m streamlit run mukul.py --server.port 8501
```

Conda (recommended on Windows for Prophet):
```powershell
conda create -n predictor python=3.10 -c conda-forge prophet
conda activate predictor
pip install -r requirements.txt
python -m streamlit run mukul.py --server.port 8501
```

2. Open http://localhost:8501 in your browser.

## Files
- `mukul.py` - Streamlit app
- `requirements.txt` - Python dependencies

## Notes
- Prophet installation can be easier with conda on Windows. If pip-installing `prophet` fails, use the conda instructions above.
- Add a remote and push to GitHub as described in the next steps.
