FROM node:20-alpine

# Create app directory
WORKDIR /app

COPY package*.json /app

# Install dependencies
RUN npm install

COPY . /app

# expose port 3000
EXPOSE 3000

CMD npm start