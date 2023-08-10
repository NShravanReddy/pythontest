[![Python application test with Github Actions](https://github.com/NShravanReddy/pythontest/actions/workflows/main.yml/badge.svg)](https://github.com/NShravanReddy/pythontest/actions/workflows/main.yml)
# pythontest
Installing conda:

wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O miniconda.sh

Run the Installer Script:

chmod +x miniconda.sh
./miniconda.sh

creating venv:

conda create -n {name of environment}

nano ~/bashrc

add conda activate -n {name of environment } to set venv as default


# Installing required files using make file
In make file under install section 

conda install --file requirements.txt

