# flask
## Running
### Exporting Flask ENV Variables

```sh
export FLASK_ENV=development
export FLASK_APP=<file.py>
export SECRET_KEY=$(openssl rand -base64 12)
```

Then install the `requirements.txt`

```sh
pip install -r requirements.txt
```

Finally, run Flask:

```sh
flask run
```
