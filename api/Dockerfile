FROM --platform=linux/amd64 node:16-alpine

COPY . .

RUN npm install

RUN npm run build

EXPOSE 4000

CMD ["npm", "run", "start:prod"]
