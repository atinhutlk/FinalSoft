FROM node
WORKDIR app
EXPOSE 3001
COPY package.json package.json
RUN npm i
COPY js .
CMD ["npm", "run", "dev"]
