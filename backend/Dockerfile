
# Use official Node.js image as a base
FROM node:14

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy all other files
COPY . .

# Expose the port your app will run on
EXPOSE 3000

# Command to run the app
CMD ["node", "index.js"]
