# Use official Node.js LTS image
FROM node:18

# Create app directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy all backend source code
COPY . .

# Expose backend port
EXPOSE 3607

# Start the backend server
CMD ["node", "server.js"]

