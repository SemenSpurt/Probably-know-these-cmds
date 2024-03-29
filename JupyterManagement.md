# Virtual environment
python -m venv venvname\
source venvname/bin/activate\
\

## Install Jupyter ipython kernel
pip install ipykernel\
python -m ipykernel install --user --name=venvname\

### List all kernels
jupyter kernelspec list \

### Uninstall Jupyter ipython kernel
jupyter kernelspec uninstall unwanted-kernel\
