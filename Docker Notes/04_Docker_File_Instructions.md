# Docker File Instructions
- Docker file is a text file with instructions for building a Docker image
- Each instruction = a layer in the image

1. FROM
- Sets the base image
- Example: FROM python:3.10 or FROM node:14

2. WORKDIR
- Sets the working directory inside the container
- All following commands run inside this directory
- Example: WORKDIR /app

3. COPY
- Copies files from host machine → container
- Used to bring application code into the image
- Example: COPY . .

4. RUN
- Executes commands during image build (install packages, update dependencies, etc.)
- Example: RUN npm install

5. EXPOSE
- Container runs on a specific port number
- Example: EXPOSE 3000

6. CMD
- Tells Docker which program to run when the container starts.
- Example: CMD ["python3", "app.py"]




