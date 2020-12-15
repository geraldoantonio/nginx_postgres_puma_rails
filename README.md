# Projeto do curso: Docker para Desenvolvedores Ruby on Rails

O curso mostra como dar os primeiros passos com o Docker para seu uso tanto em ambiente de desenvolvimento como em produção.
Serão abordados assuntos como: Conceitos iniciais do Docker, Dockerfile, Docker Hub, Docker Compose, Volumes, Networks, Ports, etc. 


## Comandos para Produção
```
docker-compose run app bundle exec rails assets:precompile RAILS_ENV=production

docker-compose run app bundle exec rails db:create RAILS_ENV=production

docker-compose run app bundle exec rails db:migrate RAILS_ENV=production
```

- Link do Curso: http://videosdeti.com.br/curso-docker-rails.html
- Professor: Jackon Pires
