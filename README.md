# PhysicsLab Guide Documentation

## Python

1. Install `uv` (only once)
   ```sh
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. Source `.bashrc` (only once)
   ```sh
   source ~/.bashrc
   ```

3. Install specific version of python (once per version)
   ```sh
   # System python version is 3.12 (2024.09.13)
   uv python install 3.12
   ```

4. Go to your project directory

5. Create virtual environment with your desired python version
   ```sh
   uv venv --python=3.12 
   ```

6. Install dependencies
   ```sh
   uv pip install numpy matplotlib scipy notebook # any packages you need
   ```

7. Activate virtual environment (every time you want to use it)
   ```sh
   source .venv/bin/activate
   ```

8. Enjoy!
