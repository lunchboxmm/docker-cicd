FROM node:4.6 as unittest
WORKDIR /app
ADD . /app
RUN echo "unit test"
RUN echo "coverage and static analysis"
RUN echo "UI tests"
RUN echo "final artifact"
RUN npm install
EXPOSE 3000
CMD npm start
