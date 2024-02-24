# online-shop
# Docker должен быть запущен на компьютере
# запуск docker: docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:management
# для запуска Celery используйте команду: celery -A myshop worker -l info
# Stripe: stripe listen --forward-to localhost:8000/payment/webhook/
# установка библиотеки redis pip install redis
# Проверьте, чтобы в базу данных было включено несколько объектов Product и инициализирован контейнер Redis платформы Docker следующей ниже командой:
# docker run -it --rm --name redis -p 6379:6379 redis
