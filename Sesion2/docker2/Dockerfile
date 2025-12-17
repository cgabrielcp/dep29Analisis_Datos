FROM python:3.9-slim

WORKDIR /app

#Copiar el archivo req a mi contenedor
COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

# Copiar todos los archivos a mi contenedor
COPY . .

EXPOSE 5000

CMD ["python", "app.py"]

