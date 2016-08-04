# Django Docker test project

### Init requirements
docker-compose run web pip install --upgrade -r requirements.txt

### Start docker deamon
docker-compose up -d

### Migrate database
docker-compose run web python manage.py migrate