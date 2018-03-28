![How to dockerize your PHP Monolith](https://www.fabridinapoli.com/images/posts/how-to-dockerize-php-monolith.png)


# How to dockerize your PHP Monolith

## Description
Having an old PHP Monolith and you don't know how to dockerize it?
Are you still using a virtual machine in your local environment?

Probably this [article](https://www.fabridinapoli.com/how-to-dockerize-your-php-monolith-part-one/) and this repo could help you!

## How it works

1. Add this line to your `/etc/hosts`
```
127.0.0.1   your-great-monolith.com
```

2. Run this command:
```
docker-compose up --build
```

3. Open your favourite browser and go to `your-great-monolith.com`


## Blog articles list about "How to dockerize your old php monolith"

* [How to dockerize your old PHP monolith - part one](https://www.fabridinapoli.com/how-to-dockerize-your-php-monolith-part-one/)

* [How to dockerize your old PHP monolith - part two: Nginx](https://www.fabridinapoli.com/how-to-dockerize-your-php-monolith-part-two-nginx/)

* [How to dockerize your old PHP monolith - part three: PHP-FPM](https://www.fabridinapoli.com/how-to-dockerize-your-php-monolith-part-three-php-fpm/)

* [How to dockerize your old PHP monolith - part four: Redis and Sphinx](https://www.fabridinapoli.com/how-to-dockerize-your-php-monolith-part-four-redis-sphinx/)

and more to come...
