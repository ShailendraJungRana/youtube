# Base image
FROM node:18

# Create working directory
WORKDIR /app

# Copy package files
COPY package*.json ./


# Install dependencies
RUN npm install

# Copy all project files
COPY . .

EXPOSE 5000

# Start the application
CMD ["npm", "start"]