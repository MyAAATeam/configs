# openprocurement.bridge.buildout

https://github.com/ProzorroUKR/openprocurement.bridge.buildout


## Setup

- Create & activate virtualenv
- `pip install -r requirements.txt`
- `git clone https://github.com/systemd/python-systemd.git /tmp/python-systemd`
- `sudo apt install libsystemd-dev`
- `cd /tmp/python-systemd`
- `make`
- `python setup.py install`
- `cd $OLDPWD`
- `rm -rf $OLDPWD`
- `python bootstrap.py`
- `bin/buildout -N`


## Run

`bin/circusd`


# Requires
- `openprocurement.buildout` on port **6543**
- `openprocurement.documentservice.buildout` on port **6548**
- `openprocurement.medicines.registry` on port **6547**
