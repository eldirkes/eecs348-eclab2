# Set the base image to use
FROM gcc:latest

# Copy the C program into the container
COPY nfl.c .

# Compile the C program
RUN gcc -o nfl nfl.c

# Set the command to run when the container starts
CMD ["./nfl"]