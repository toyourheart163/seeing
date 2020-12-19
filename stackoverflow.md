I make a python project to monitor *.html *.css *.js *.py

if they change or delete or add. it will reload devlop server.

Install seeing

```bash
pip install gunicorn seeing
```

Usage

```python
seeing -c gunicorn project_name.wsgi
```
