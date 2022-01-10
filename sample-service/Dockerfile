FROM node:12.22-slim
WORKDIR /sample-service
COPY api/package.json ./
RUN npm install
COPY api/ /sample-service
EXPOSE 8123
CMD [ "node", "app.js" ]