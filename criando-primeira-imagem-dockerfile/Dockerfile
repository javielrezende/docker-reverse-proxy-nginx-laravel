FROM nginx

WORKDIR /app

# Modo 1
# RUN apt-get update
# RUN apt-get install vim -y

# Modo 2
# RUN apt-get update && apt-get install vim -y

# Modo 3
RUN apt-get update && \
    apt-get install vim -y

COPY html/ /usr/share/nginx/html