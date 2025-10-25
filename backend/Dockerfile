# Step 1: Use a Node base image
FROM node:14-alpine

# Step 2: Set working directory
WORKDIR /app

# Step 3: Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Step 4: Copy backend code
COPY . .

# Step 5: Expose port
EXPOSE 5000

# Step 6: Start the backend server
CMD ["npm", "start"]
