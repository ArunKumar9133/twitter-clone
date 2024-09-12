

---

## How to use:

First, clone the repository and

```shell
cd twitter-clone
```

Set up the backend:

```shell
cd backend
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

Create the database:
```python
$ python3 # open the shell
import app
app.db.create_all()
```

Run the application
```shell script
python3 app.py
```

Set up the frontend in a new terminal window:

```shell
cd frontend
npm install
npm start
```
