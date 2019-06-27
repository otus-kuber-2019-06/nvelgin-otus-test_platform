FROM python:3.7.3-alpine3.9
RUN apk --no-cache add curl
WORKDIR app
RUN chown -R 1001 /app
USER 1001
CMD python3 -m http.server 8000
