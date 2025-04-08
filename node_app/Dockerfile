# Use a modern Node.js version that supports Object.hasOwn()
FROM node:18-alpine

WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy remaining source files
COPY . .

EXPOSE 3000

CMD ["node", "server.js"]

