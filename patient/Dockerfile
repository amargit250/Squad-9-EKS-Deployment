# Use a Node.js official image
FROM node:16-alpine

# Create and set the working directory
WORKDIR /usr/src/app

# Copy package.json 
COPY package.json ./

# Install the dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port your service runs on (in this case, 3000)
EXPOSE 3000

# Run the app
CMD ["npm", "start"]
