# build
  sudo docker build .
  sudo docker-compose build

# run
  sudo docker-compose run app sh -c ""
  ## sh -c "" wykonuje w shellu komendę ""

  sudo docker-compose run app sh -c "django-admin.py startproject app ."