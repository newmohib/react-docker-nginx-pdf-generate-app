#### Make the Script Executable: Run the following command to make the script executable:

    chmod +x script.sh && ./script.sh

### Run with Docker

    docker build -t angular-sample-app .
    docker run -p 3002:80 angular-sample-app

#### Create any new project with using angular CLI follow this step
- copy and past 4 files from here 
 - .dockerignore
 - default.conf
 - Dockerfile
 - script.sh
- add this command into package.json file as script
 - "start:prod": "chmod +x script.sh && ./script.sh"
- Run the application with Docker
 - npm run start:prod
 - or
 - chmod +x script.sh && ./script.sh
