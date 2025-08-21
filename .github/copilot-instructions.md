# GitHub Copilot Instructions

## Python Docstring Standards

- **Use Google-style docstrings** for all Python functions, classes, and methods.
- **At the beginning of every Python script or module**, include a one-line docstring summarizing the file, e.g., `"""This module contains pADME models."""`
- For functions, classes, and methods, use the following Google format:

```python
def example_function(param1: int, param2: str) -> bool:
    """Summary of what the function does.

    Args:
        param1 (int): Description of param1.
        param2 (str): Description of param2.

    Returns:
        bool: Description of the return value.
    """
    # ...existing code...
```

- **Docstrings must be present** for all public functions, classes, and methods.
- **Private/internal functions** (starting with `_`) should also have docstrings, but they can be brief.
- **Docstrings should be consistent** throughout the codebase.
- **Do not use reStructuredText or NumPy style**; always use Google style.

## General Copilot Usage

- Prefer clear, concise, and consistent code suggestions.
- Follow existing code style and formatting.
- When in doubt, add a docstring following the above conventions.
- For new files, always start with a one-line module docstring as described above.
