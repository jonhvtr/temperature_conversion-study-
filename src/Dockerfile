FROM node:22.0.0
WORKDIR /app
COPY packege*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]