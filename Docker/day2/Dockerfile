#FROM ubuntu
#RUN apt-get update
#RUN ["apt-get", "install","figlet"]

#task2 Added CMD

#CMD figlet -f script hello world!

#added multiple CMD

#CMD figlet -f script Hello World2!

#CMD figlet -f script Hello Aswin!

#task3 added figlet with entrypoint
#ENTRYPOINT ["figlet","-f","script"] 

#task 4 Entry point and CMD

#ENTRYPOINT ["figlet","-f","script"]

#CMD ["what is going on?"]
 

#task 5 compiling c file

FROM ubuntu
RUN apt-get update
RUN apt-get install -y build-essential
COPY hello.c /
RUN make hello
CMD /hello
