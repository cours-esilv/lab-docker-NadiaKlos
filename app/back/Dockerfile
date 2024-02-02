FROM python:3.12

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

# Ajout de la variable d'environnement
ENV CURRENT_ENVIRONMENT=production

CMD [ "python", "app.py" ]



