# Virtual environment
python -m venv venvname\
source venvname/bin/activate\
\
pip install ipykernel\
python -m ipykernel install --user --name=venvname\
