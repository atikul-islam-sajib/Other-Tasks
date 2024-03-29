# -------------------------------
# Installation:
# install Python 3.10+ on your system, restart system
# Example here: Windows 11, Linux, MacOS

# -------------------------------
# Installation:
c:
cd C:\(...)\Lec5_ Model Drift

# Windows:
python -m venv .venv
.venv\Scripts\activate.bat

# Linux, MacOS:
.venv/Scripts/activate

pip install -r requirements.txt

# -------------------------------
# Launch:
c:
cd C:\(...)\Lec5_ Model Drift

# Windows:
.venv\Scripts\activate.bat
# Linux, MacOS:
.venv/Scripts/activate

spyder
# jupyter notebook


- **Drift Factor**: Determines the magnitude of drift in data.
  - **Large Drift**: High `drift_factor`, resulting in significant data alterations.
  - **Small Drift**: Low `drift_factor`, causing minor data changes.
- **Impact on Model**:
  - Large drift leads to a substantial drop in model accuracy due to significant differences between training and test data.
  - Small drift has a minimal impact on model performance, indicating the model's resilience to slight data variations.

