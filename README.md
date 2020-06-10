# How to get up and running
Install [python 3](https://www.python.org/downloads/) and then follow the
subsequent code for command line and/or git utilities:
```bash
# install bln python package
pip install bln

# from command line
bln upload -p <project_id> -k <api_key> *.csv  # automatically saves api key
bln upload -p <project_id> *.csv               # uses saved api key

# within git repo
bln upload -p <project_id> -k <api_key> *.csv # automatically saves api key and project id
bln upload *.csv                              # uses saved api key and project id
```
