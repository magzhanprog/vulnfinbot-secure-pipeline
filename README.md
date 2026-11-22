# Mini-VulnFinBot — Secure CI/CD Pipeline

A lightweight Flask-based AI financial assistant demonstrating end-to-end DevSecOps practices: automated testing, SAST, dependency & container scanning, DAST, and AI-specific security controls.

## Technologies Used
- **Backend:** Python 3.12, Flask, Gunicorn
- **Testing:** pytest
- **CI/CD:** GitHub Actions
- **SAST:** Bandit, Semgrep (custom rules)
- **SCA & Container Security:** pip-audit, Docker, Trivy
- **DAST:** OWASP ZAP Baseline Scan

## Setup & Local Execution (Windows PowerShell)
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python run.py