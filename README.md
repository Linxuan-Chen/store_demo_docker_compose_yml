# The docker-compose.yml for integrating store_demo 

Place the docker-compose.yml (for prod container) or docker-compose.dev.yml (for dev container) file alongside the frontend and backend folders. The file structure should be: 
project-root/  
│  
├── frontend/ # Frontend code  
├── backend/ # Backend code  
└── docker-compose.yml # Docker Compose configuration  
Run `docker-compose up --build` to start production container
Run `docker-compose -f docker-compose.dev.yml up ` to start dev container (Database access is restricted due to AWS free tier limits, so you won't be able to start the server with the command. Please use production server instead.)
