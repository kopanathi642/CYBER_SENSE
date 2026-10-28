What's included?
1. URL phishing detector
- Detect suspicious URL structures and phishing-related keywords.
- Identify IP-based URLs, punycode domains and other warning signs.
- Assign a risk score from 0–100.



2. Automatic browser monitoring
- Chrome extension checks visited URLs.
- Shows warnings for suspicious and high-risk results.
- Sends URLs to your local backend, not a cloud service.



3. Web dashboard and API
- Scan URLs through a dark-themed dashboard.
- Flask REST API for detection.
- Displays risk scores and explanations.



4. Optional machine-learning training
- Includes train_model.py.
- Supports training from a labelled CSV dataset.
- The current detector uses explainable heuristics; the optional trained model is not yet integrated into live scanning.



How to run it
1. Extract the ZIP file.
2. Open the extracted project folder in VS Code.
3. Open the VS Code terminal and run:
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python backend/app.py


4. Open **http://127.0.0.1:5000** in Chrome.
5. To enable automatic browsing checks, open chrome://extensions, enable Developer mode, and select Load unpacked. Choose the project's extension folder.
