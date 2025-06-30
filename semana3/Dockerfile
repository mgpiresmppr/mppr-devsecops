FROM node:18
# WORKDIR /usr/src/app
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
# CMD ["npm", "start"]
CMD [ "node", "app.js" ]