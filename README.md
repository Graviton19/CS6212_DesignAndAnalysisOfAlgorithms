# Runtime vs Scaled Theoretical Complexity

This project measures and analyzes the runtime of a specific code snippet and compares it against the theoretical complexity 
of **O(log₂(n) · log₂(log₂(n)))**. The runtimes are measured across varying input sizes, and results are plotted alongside scaled theoretical values for comparison.

## Project Structure
- `experiment.py` — main Python script containing the experiment code
- `graph.png` (optional) — saved runtime vs theoretical graph
- `requirements.txt` — list of dependencies (optional if only using standard libraries + matplotlib/numpy)

## Requirements
This project uses Python 3.8+ and the following libraries:
- `matplotlib`
- `numpy`

You can install dependencies and run the program with:
```bash
pip install matplotlib numpy
python experiment.py
