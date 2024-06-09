## Data analysis exercise

### Environment setup

This instructions are for linux operating systems.

Create python virtual environment:

```
python3 -m venv .venv
```
Install required libraries:

```
pip install -r requirements
```

### Data Source

The data must be placed in the `/data` directory.

### Content

* `uptime_analysis.ipynb`: this notebook has been created in first place. It tries to address the detection of anomalies in the uptime telemetry.
* `position_analysis.ipynb`: this notebook makes the coordinated transformation from TEME to lat,long and in the end tries to find a correlation between the position and the failures.