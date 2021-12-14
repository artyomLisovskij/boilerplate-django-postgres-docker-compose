# simpliest django(uvicorn)+postgresql+nginx docker-compose (ready for production and dev)
To run in production:
`docker-compose up -d`

Site available on 8000 port.

## DEV
Run in dev(with hot reload):
`docker-compose -f docker-compose.yaml -f docker-compose.dev.yaml up -d`

You can make any changes in code, they will appear automatically. If you want to execute something with manage.py use:
`docker-compose exec app makemigrations`
`docker-compose exec app createsuperuser`
and so on.
