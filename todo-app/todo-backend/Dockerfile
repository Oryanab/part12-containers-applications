FROM node:16

WORKDIR /src/backend/app

COPY . .

RUN npm ci --only-production

CMD npm start

# docker build -t <name of image> <. = where is the dockerfile located>  
# docker container run -it --name hello-node node:16 bash
# docker start -i  dazzling_sutherland
# docker run -it todo-backend 
# docker build -t todo-backend . 