Task manager
============

Task manager project built with Ruby on Rails and React

Instruction
-----------

1. Build the project:

```sh
docker-compose build
```

2. Install gems inside of the docker container:

```sh
docker-compose run --rm web bash -c "bundle install"
```

3. Setup the database:

```sh
docker-compose run --rm web bash -c "rails db:create db:migrate"
```

4. Run the project:

```sh
docker-compose up
```

App will be available on `localhost:3000`
