**Activate the virtual environment**

```
source bin/activate/bin/activate
```

**Install all packages**
```
pip3 install -r requirements.txt
```

**Run the tests**

Activate the virtual environment

```
python3 -m pytest backend/tests
```

**Run the application and API**

Make sure to activate the virtual environment.

```
python3 -m backend.app
```

**Run a peer instance**

Make sure to activate the virtual environment.

```
export PEER=True && python3 -m backend.app
```