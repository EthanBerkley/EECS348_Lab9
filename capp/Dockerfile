# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY p1.c .
# Compile the C program
RUN gcc -o p1 p1.c
# Set the command to run when the container starts
CMD ["./p1"]