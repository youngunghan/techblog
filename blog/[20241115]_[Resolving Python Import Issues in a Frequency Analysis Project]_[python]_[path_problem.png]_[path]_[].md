# Resolving Python Import Issues: A Practical Guide

## Project Structure

```
vision-ml-project/
├── src/
│   └── vision_utils/
│       ├── __init__.py
│       ├── preprocessing/
│       │   ├── __init__.py
│       │   ├── augmentation.py
│       │   └── transforms.py
│       ├── models/
│       │   ├── __init__.py
│       │   └── network.py
│       └── train.py
├── tests/
├── setup.py
└── README.md
```

## The Challenge

When trying to run the training script directly:

```bash
python /path/to/vision-ml-project/src/vision_utils/train.py --data-dir /path/to/dataset
```

We encounter this error:
```python
Traceback (most recent call last):
  File "train.py", line 3, in <module>
    from vision_utils.preprocessing import transforms
ModuleNotFoundError: No module named 'vision_utils'
```

## Root Cause Analysis

**Python's Module Search Behavior:**
- Python first looks in the directory containing the executed script
- Then searches through PYTHONPATH directories
- Finally checks installed packages

When running the script directly, Python cannot find the `vision_utils` package because the `src` directory is not in its search path.

## Solution Implementation

### Method 1: Using PYTHONPATH
```bash
export PYTHONPATH="/path/to/vision-ml-project/src:$PYTHONPATH"
python src/vision_utils/train.py --data-dir /path/to/dataset
```

### Method 2: Module-style Execution
```bash
python -m vision_utils.train --data-dir /path/to/dataset
```

### Method 3: Development Installation
```bash
# From project root
pip install -e .
```

## Best Practices

1. **Project Structure**
   - Keep all source code under `src/`
   - Use meaningful package names
   - Include `__init__.py` files

2. **Import Style**
   ```python
   # Preferred
   from vision_utils.preprocessing import transforms
   
   # Avoid
   from ..preprocessing import transforms
   ```

3. **Development Setup**
   - Use virtual environments
   - Install package in editable mode
   - Document dependencies properly

## Key Learnings

1. Understanding Python's import system is crucial
2. Project structure affects import behavior