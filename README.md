 # to create virtual env
 uv venv env --python cpython-3.12.13-windows-x86_64-none
 paste env\Scripts\activate 

 ** notes
 3.12.13 not working properly so im using 3.11.13
# install using uv 
 uv python install 3.11.13 
## to check python list
uv python list  
## to create virtual environment 
uv venv env --python cpython-3.11.13-windows-x86_64-none
## to activate virtual env
env\Scripts\activate
## to intall reuirements from txt file
uv pip install -r requirements.txt