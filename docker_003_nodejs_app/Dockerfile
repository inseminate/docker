FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 8787

CMD ["node","server.js"]

# Usage : docker run -p (localport):(docker exposed port)  (sha-256 encrpted id)

# docker run -p 8787:8787 bc8072