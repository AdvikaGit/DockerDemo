From node

WORKDIR /myangularapp

COPY . .
RUN npm install -g http-server

EXPOSE 3380
CMD ["http-server", "--port", "3380"]