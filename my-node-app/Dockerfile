FROM node:16-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

# Expose the application port
EXPOSE 3000

# Command to run the application
CMD ["node", "app.js"]
