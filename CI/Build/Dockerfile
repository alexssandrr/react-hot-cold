FROM node:latest
RUN apt-get update && apt-get install git -y
RUN git clone https://github.com/alexssandrr/react-hot-cold.git
WORKDIR /react-hot-cold
RUN npm i
RUN npm run-script build
