# Use an official Node.js runtime as the parent image
FROM node:14

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install dependencies inside the container
RUN npm install

# Copy the rest of the application to the container
COPY . .

# Specify the port the app will listen on
EXPOSE 3000

# Define the command to run the app
CMD ["node", "index.js"]
