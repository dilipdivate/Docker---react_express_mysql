FROM node:16.13-alpine3.13
WORKDIR /app
COPY package*.json ./
COPY ./ ./
RUN npm i
CMD ["npm", "run", "start"]

# docker build -f Dockerfile -t server .
# docker run -it -p 4002:3011 server