FROM node:lts-alpine

WORKDIR /app

RUN apk upgrade &&\
apk add git &&\
git clone https://github.com/horvathg13/ProjectLab-Vue3js.git

RUN cd ProjectLab-Vue3js

WORKDIR /app/ProjectLab-Vue3js
RUN npm install

CMD ["npm", "run", "dev", "--", "--host","0.0.0.0"]