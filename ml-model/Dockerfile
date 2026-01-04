# ml-model/Dockerfile
FROM python:3.10

WORKDIR /app
COPY requirement.txt .
RUN pip3 install --no-cache-dir -r requirement.txt

COPY . .

EXPOSE 5001
CMD ["python3", "main.py"]
