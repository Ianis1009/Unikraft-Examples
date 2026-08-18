FROM gcc:12

WORKDIR /app

COPY hello.c .

RUN gcc -static -O2 -o hello hello.c

CMD ["/app/hello"]