Setting up & usage of virtual python environment (venv)
``` shell
python3 -m venv myenv  # Create the environment 
source myenv/bin/activate  # Activate the environment

pip install --upgrade pip 
pip install pandas
pip install jupyter  # Install Jupyter
pip install -U scikit-learn

jupyter notebook  # Launch Jupyter Notebook
deactivate
```