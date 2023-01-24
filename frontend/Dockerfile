FROM node:16
WORKDIR /app/frontend
COPY ./package.json /app/frontend
RUN npm install --force
COPY . .
CMD ["npm", "run", "dev"]