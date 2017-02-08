# wwc-lightning-talks

Example project for the February 2017 Women Who Code Lightning Talks

## Setup

```
# Make sure to use Python 2.7

# Check out the project from git
git clone https://github.com/makearl/wwc-lightning-talks.git
cd wwc-lightning-talks

# Install pip if you don't already have it (see http://pip.readthedocs.org/en/latest/installing.html)
pip install virtualenvwrapper
# If you are using Windows, you will need the Windows wrapper as well:
# pip install virtualenvwrapper-win

mkvirtualenv wwc-lightning-talks
workon wwc-lightning-talks

# Install dependencies
python setup.py install

# Run tests
python setup.py test
```

