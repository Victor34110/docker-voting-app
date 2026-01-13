FROM python

#repertoire dans le container
WORKDIR /app

COPY requirements.txt .

#installe les dependances
RUN pip install --no-cache-dir -r requirements.txt

# copie tous le code
COPY . .

# sur le port 80
EXPOSE 80

CMD [ "python", "app.py"]