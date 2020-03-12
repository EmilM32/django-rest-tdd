# build
  ```
  sudo docker build .
  sudo docker-compose build
  ```

# start project
  ```
  sudo docker-compose run app sh -c "django-admin.py startproject app ."
  ```

# start app
  ```
  sudo docker-compose run app sh -c "python manage.py startapp core"
  ```

# unit test
  ```
  sudo docker-compose run app sh -c "python manage.py test && flake8"
  ```