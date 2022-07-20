###### Works on - debian based distros(depends on dpkg)

###### Requirements - python3, pip3, virtualenv

##### Steps -

virtualenv .venv

source .venv/bin/actiavte

pip install -r requirements.txt

./list_libraries <path_to_binary> <path_to_xlsx_file>

##### Eg:

./list_libraries /usr/bin/vim ~/vim-lib.xlsx
