[![Build Status](https://travis-ci.org/H4RP3R/SF_E1.12_Hangman_testing.svg?branch=master)](https://travis-ci.org/H4RP3R/SF_E1.12_Hangman_testing)
## How to run.
```
git clone https://github.com/H4RP3R/SF_E1.12_Hangman_testing.git
cd SF_E1.12_Hangman_testing
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python3 game.py
```
## Running tests
```
python -m unittest tests/test_unittest.py -v
coverage report -m
```
```
Name      Stmts   Miss  Cover   Missing
---------------------------------------
game.py      53     14    74%   11, 37-38, 68-75, 79-82
```
