from node:14.14.0-alpine
workdir '/app'
copy ./package.json ./
run npm install
copy . .
expose 5000
cmd ["npm", "run", "start"]