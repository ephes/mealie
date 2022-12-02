postgres: postgres -D dev/data/postgres/  # initdb dev/data/postgres/
uvicorn: PYTHONUNBUFFERED=true $VIRTUAL_ENV/bin/python mealie/app.py
vue: cd ~/projects/mealie/frontend && yarn start
# jupyterlab: PYTHONPATH=$(pwd) jupyter-lab
# caddy: cd frontend && caddy run --config Caddyfile
