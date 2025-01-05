# Use Node.js official image
FROM node:18

# Set working directory
WORKDIR /usr/src/app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install --production

# Copy application code
COPY . .

# Expose application port
EXPOSE 3000

# Start application
CMD ["npm", "start"]
