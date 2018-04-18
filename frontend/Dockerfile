FROM node:8
RUN mkdir /frontend
ADD . /frontend
WORKDIR /frontend
run npm i
EXPOSE 80
CMD ["npm", "start"]