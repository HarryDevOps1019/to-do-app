FROM node:18-alpine3.12

# Set working directory inside container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy all source files
COPY . .

# Expose the port your app runs on
EXPOSE 4000

# Start the app (replace server.js with your actual entry file)
CMD ["node", "server.js"]
