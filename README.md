## Data analysis exercise

### Environment setup

The following commands work in linux based operating systems.

Create python virtual environment:

```
python3 -m venv .venv
```
Activate virtual env:

```
source .venv/bin/activate
```
Install required libraries:

```
pip install -r requirements.txt
```

### Data Source

The data must be placed in the `/data` directory.

### Content

* `uptime_analysis.ipynb`: this notebook has been created in first place. It tries to address the detection of anomalies in the uptime telemetry.
* `position_analysis_v2.ipynb`: this notebook makes the coordinates transformation from TEME to lat,long, and in the end tries to find a correlation between the position and the failures.