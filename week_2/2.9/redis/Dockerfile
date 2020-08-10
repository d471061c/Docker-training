FROM redis:6.0-alpine

COPY redis.conf /app/redis.conf
EXPOSE 6379:6379

CMD [ "redis-server", "/app/redis.conf" ]