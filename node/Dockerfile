FROM node:12-alpine

# Set the working directory
WORKDIR /var/www/hotelszone_node_partner

# Install dependencies
COPY package.json .
RUN npm install

# Copy the code
COPY . .

# Expose the app port
EXPOSE 3000

# Start the app
CMD ["npm", "start"]
