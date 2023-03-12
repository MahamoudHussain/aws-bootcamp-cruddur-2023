FROM node:16.18

ENV PORT=3000

COPY . /frontend-react-js
WORKDIR /frontend-react-js
RUN npm install

COPY run.sh /frontend-react-js/run.sh
RUN chmod +x /frontend-react-js/run.sh

EXPOSE ${PORT}
CMD ["/frontend-react-js/run.sh"]