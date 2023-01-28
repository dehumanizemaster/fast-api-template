FROM python:3.9  
WORKDIR /app     
RUN pip3 install fastapi
RUN pip3 install "uvicorn[standard]"
COPY . /app  
CMD ["uvicorn", "authen_access:app", "--host", "127.0.0.1", "--port", "8000"]
