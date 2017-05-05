# Twitter Stream
ADW Twitter Stream

# How to setup 
Install python and follow below items:

```
$: sudo apt-get install virtualenv
$: sudo apt-get install python-pip
$: sudo apt-get install python-matplotlib
```
## Check version 
```
$: virtualenv --version
```
## Make virtual environment
```
$: virtualenv venv
```
### Activate virtual environment 
```
$: source venv/bin/activate
```
## Install pacakges 
```
pip install -r requirements.txt
```
## Start twitter streaming
```
$: python twitter_streaming.py > twitter_data.txt
```
## Install a package
```
$: pip install [package-name]
$: pip freeze
$: pip freeze > requirements.txt
```