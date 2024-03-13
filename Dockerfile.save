# Create app directory
WORKDIR /app
# Install app dependencies
COPY package*.json ./
RUN npm install
# Copying rest of the application to app directory
COPY . /a
# Expose the port and start the application
Expose 8080
CMD ["npm","start"]
