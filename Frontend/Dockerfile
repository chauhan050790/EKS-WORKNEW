FROM node:10
WORKDIR /opt/app
COPY package*.json ./
COPY . .
RUN CI=true
# Installs all node packages
RUN npm i
CMD ["npm", "run", "start"]