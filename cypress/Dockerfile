From cypress/browsers

RUN mkdir /app
WORKDIR /app

COPY ./app
RUN npm install

RUN $(npm bin/cypress verify

RUN ["npm", "run", "cy:run_spec"]