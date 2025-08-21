# Commit Message Instructions

- **ALWAYS generate commit messages using the pattern below. DO NOT use any other format.**
- **Pattern:** `[<type> :emoji:] <short summary>`
  - Bullet points (optional): Add one or more bullet points below the summary to describe details, changes, or rationale.
  - Each bullet point should start with `- `.

- **type:** One of `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `experiment`
- **scope:** (optional) The affected module, file, or feature
- **short summary:** Brief description (max 50 characters)
- **longer description:** (optional) More details if necessary
- **emoji:** Use the relevant emoji for the type (see examples).

**Examples:**
- `[feat :sparkles:] add PADMEDataset class`
  - Add support for PADME embeddings in dataset
  - Improve compatibility with graph models
- `[fix :wrench:] correct PK parameter calculation`
  - Fix division by zero error
  - Update docstring for clarity
- `[docs :books:] update API reference overview`
  - Add documentation for API calls in Python
- `[refactor :recycle:] simplify data preprocessing logic`
  - Replace pandas successive methods with method-chaining to improve readability and efficiency
- `[test :white_check_mark:] add unit tests for PADMEDataset`
  - Add unit test to check the health of data preprocessing pipeline
- `[chore :broom:] update dependencies`
  - Add tenacity dependency to the requirements
- `[experiment :test_tube:] ran new experiment in notebook`
  - Run experiment to test data preprocessing pipeline
