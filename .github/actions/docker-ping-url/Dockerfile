FROM python:alpine3.19

WORKDIR /github/workspace

COPY requirements.txt .
RUN python -m pip install --no-cache-dir -r requirements.txt

COPY main.py .

CMD ["python", "main.py"]
