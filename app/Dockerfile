FROM node:16

# Creates directory to contain app code inside the image
WORKDIR /usr/src/app

# Copy package.json and package-lock.json files 
COPY package*.json ./

# Install dependencies
RUN npm install

# Bundle application's source code inside image
COPY . .

EXPOSE 8080
CMD [ "node", "index.js" ]
