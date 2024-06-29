FROM node:16

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the backend code
COPY . .

# Expose the port the app runs on
EXPOSE 8070

# Command to run the backend application
CMD ["node", "server.js"]






