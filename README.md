# MuJoCo Wheel + Base Controller

Minimal project containing only the dual-actuator reaction-wheel pendulum controller and its XML model.

## Files
- `wheel_and_base.py`: Stabilizing controller for wheel motor + base motor.
- `reactionwheel_basemotor.xml`: MuJoCo model with realistic lighting/background and actuator setup.
- `requirements.txt`: Python dependencies.

## Requirements
- Python 3.10+
- GPU/graphics environment that can open MuJoCo viewer windows

## Setup
```bash
python -m venv .venv
.venv\\Scripts\\activate
pip install -r requirements.txt
```

## Run
```bash
python wheel_and_base.py
```

The script starts with a small tilt (~8 deg) and prints controller telemetry once per second.
