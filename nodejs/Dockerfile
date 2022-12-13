from node

COPY package* .
RUN npm install
COPY . .
RUN NODE_ENV=production npm run build

CMD ["npm", "start"]