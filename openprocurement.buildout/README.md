# openprocurement.buildout

https://github.com/ProzorroUKR/openprocurement.buildout


## Setup

- Create & activate virtualenv
- `pip install -r requirements.txt`
- `python bootstrap.py`
- `bin/buildout -N`

## In some environments required

- `apt install libsodium-dev`

## Run

`bin/pserve etc/openprocurement.api.ini --reload`
