# cos_783_assignment6
Several digital forensic investigation techniques can benefit from the application of artificial intelligence (AI) techniques to enhance efficiency and accuracy. 

Setting Up Environment

Download and install Anaconda 
Link: https://www.anaconda.com/download/success
It is a distribution of python therefor take care of version control if python is already installed.

For VS code
- Install python extensions
- Install Jupyter extensions

Install Jupyterlabs

- pip3 install jupyterlab    

Install Spacy

- conda install -c conda-forge spacy
- conda install -c conda-forge spacy-transformers
- pip install spacy-lookups-data
- python -m spacy download en_core_web_sm

Create spacy env

- python -m venv spacy_env    
- Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass [might need this]
- spacy_env\Scripts\activate [windows]
- pip install ipykernel   
- pip install spacy
- python -m pip install pandas
- pip install openpyxl    
- python -m spacy download en_core_web_sm
