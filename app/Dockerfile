# Define base image
FROM node:7.7.2-alpine

# Specify working directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json .
RUN npm install --quiet

# Copy app source
COPY . .

# Tell the port number the container should expose
EXPOSE 8080

# Run the application
CMD ["node", "index.js"]
