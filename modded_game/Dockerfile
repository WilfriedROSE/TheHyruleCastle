FROM node:latest

#créer une direction jusqu'a l'application
WORKDIR /conteneurise_mode_game

#installer les fichiers
COPY package*.json . 
# RUN sudo apt updade

RUN npm install && npm install -g typescript

COPY . .

RUN tsc main.ts

CMD ["node",  "main.js"]

