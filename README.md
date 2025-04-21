
## 🐳 Running with Docker

You can easily run this project using Docker and Docker Compose. This setup will start the backend (Node.js/Express), frontend (React), and MongoDB services in isolated containers.

### Requirements
- **Docker** and **Docker Compose** installed on your system
- No need to install Node.js or MongoDB locally

### Project-specific Docker Details
- **Node.js version:** 22.13.1 (as specified in Dockerfiles)
- **MongoDB:** Uses the official `mongo:latest` image
- **Ports Exposed:**
  - Backend (server): **5000**
  - Frontend (client): **3000**
  - MongoDB: **27017**

### Environment Variables
- If you have environment variables for the backend or frontend, you can add a `.env` file in the respective `Server` or `client` directories and uncomment the `env_file` lines in the `docker-compose.yml`.

