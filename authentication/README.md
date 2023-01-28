========== Run on local machine =========
=========================================
$ uvicorn authen_access:app --host 127.0.0.1 --port 8000



============= Run on Docker =============
=========================================
$ docker build -it authen_access .
$ docker run -dp 8000:8000 authen_access
