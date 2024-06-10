FROM node:latest
RUN apt-get update && apt-get install git -y
RUN git clone https://github.com/alexssandrr/react-hot-cold.git
WORKDIR /react-hot-cold
RUN npm install
RUN npm run build
RUN npm install -g serve
CMD blad
