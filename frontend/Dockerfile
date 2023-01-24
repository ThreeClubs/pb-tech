FROM node:16
WORKDIR /app/frontend
COPY package.json .
RUN npm i --force
COPY . .
EXPOSE 5173
CMD ["npm", "run", "dev"]