# Imagen base oficial de Python
FROM python:3.12-slim

# Crear directorio de trabajo en el contenedor
WORKDIR /app

# Copiar archivos del proyecto
COPY . .

# Instalar dependencias
RUN pip install --no-cache-dir -r requirements.txt

# Exponer el puerto para Flask
EXPOSE 5002

# Comando para ejecutar el servidor
CMD ["python", "app.py"]
