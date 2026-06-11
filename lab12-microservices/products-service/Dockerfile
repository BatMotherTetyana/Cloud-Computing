FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
# ЭТА СТРОКА САМАЯ ВАЖНАЯ - убедись, что она есть!
COPY . . 
EXPOSE 3002
CMD ["node", "server.js"]