FROM node:16.18

ENV PORT=3000

COPY . /frontend-react-js
WORKDIR /frontend-react-js
RUN npm install
EXPOSE ${PORT}
CMD ["npm", "start"]
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]