# IS601homework3---summer2024

# Submission Details

# Installation Instructions

1. Install Python/Pip/Virtualenv, or ensure it is installed. 
```
sudo apt update -y
sudo apt install python3-pip
python3 --version
pip3 --version
pip3 install virtualenv
virtualenv --version
```

2. Clone this repo
```
git clone git@github.com:fcamacho3/IS601homework3---summer2024.git
cd IS601homework3---summer2024
```

3. Create virtual environment\
Use `ls` to ensure `venv` folder is created\
Install project requirements
```
virtualenv venv
ls
```
4. Install requirements
```
pip3 install -r requirements.txt
```
If needed install pytest separately
```
pip3 install pytest pytest-pylint pytest-cov
```

5. Run the pytest to see 100% coverage
```
pytest --pylint --cov
```



