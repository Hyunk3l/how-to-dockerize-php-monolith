FROM redis:2.8-32bit

COPY ./docker/redis/conf/redis.conf /usr/local/etc/redis/redis.conf

CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]