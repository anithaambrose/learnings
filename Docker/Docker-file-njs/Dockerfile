# Base image
FROM node:18
# Set working directory
WORKDIR /app
# Copy package files and install dependencies
COPY package*.json ./
RUN npm install
# Copy the rest of the app source code
COPY . .
# Expose the port the app runs on
EXPOSE 3000
# Start the application
CMD ["npm", "start"]
