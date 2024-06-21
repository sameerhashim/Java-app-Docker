# 1st step: Get the base image

FROM openjdk:11

# 2nd step: Create a working directory to keep all the files
 
WORKDIR /app

# 3rd step: Code Copy to the image for running in container

COPY hello.java /app

# 4th step: Compile the code

RUN javac hello.java

# Now ready to run
 
CMD ["java","hello"]
