# Step 1: Use Node image
FROM node:14-alpine

# Step 2: Set working directory
WORKDIR /app

# Step 3: Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Step 4: Copy frontend code
COPY . .

# Step 5: Expose port
EXPOSE 3000

# Step 6: Start React development server
CMD ["npm", "start"]
