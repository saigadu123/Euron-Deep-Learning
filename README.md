# Euron-Deep-Learning

#### Command to install the UV in powershell
- iwr https://astral.sh/uv/install.ps1 -useb | iex

#### virtual Environment with UV
- uv venv .venv --python=3.10

#### Activation of Virtual Environment
- .venv/Scripts/activate

#### Installing Libraries
- uv pip install notebook ipykernel

### To add dependencies in UV environment
- uv init
- uv add <package name>