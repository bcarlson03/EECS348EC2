# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY Cproblem2.c .
# Compile the C program
RUN gcc -o Cproblem2 Cproblem2.c
# Set the command to run when the container starts
CMD ["./Cproblem2"]