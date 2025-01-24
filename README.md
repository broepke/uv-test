# Basics of UV Package and Environment Management

[Docs](https://docs.astral.sh/uv/getting-started/features/)

1. Navigate to your project directory

   ```bash
   uv init uv-test
   ```

2. Create a new virtual environment

   ```bash
   uv venv
   ```

3. Add or remove packages to your virtual environment

   ```bash
   uv add pandas seaborn scikit-learn

   uv remove pandas
   ```

4. Add packages from a requirements file

   ```bash
   uv add -r requirements.txt
   ```

5. Export your virtual environment

   ```bash
   uv sync
   ```

6. See a tree of dependencies

   ```bash
   uv tree
   ```
