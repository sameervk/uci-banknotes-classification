# uci-banknotes-classification
Detection of forged notes using pytorch and scikit-learn libraries


### Installing python libraries

* Python version: 3.11.5

* Install Poetry

* Execute the following commands in sequence from the repository
	1. `poetry init` 
	2. `poetry shell`
	3. `poetry install` : to install libraries from poetry.lock. 

* Pytorch is missing as there is poetry cannot find the required version. So, use pip to install pytorch
	`pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu`

* Or, if cannot be bothered to use poetry, then use `requirements.txt` to install all the libraries.
