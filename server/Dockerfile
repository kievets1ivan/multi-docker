from node:14.14.0-alpine
workdir '/app'
copy ./package.json ./
run npm install
copy . .
cmd ["npm", "run", "start"]