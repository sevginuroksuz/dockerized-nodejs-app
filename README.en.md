[🇹🇷 Türkçe](README.md) | [🇬🇧 English](README.en.md)

---

# 🐳 Dockerized Node.js App  

This project demonstrates how to containerize a **Node.js** application using Docker.  
It provides a modern and portable development environment with **MongoDB and Redis** integration.

## About the Project  
This repository explains **how to run a Node.js application using Docker and Docker Compose**.  
The project includes the following components:

- **Node.js** – Backend development  
- **Docker & Docker Compose** – Container management  
- **MongoDB** – Database management  
- **Redis** – Caching  

---

## Installation  

### Requirements  
Before running this project, make sure the following tools are installed on your system:

- [Node.js](https://nodejs.org/)  
- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)  

### Clone the Repository  
```sh
git clone https://github.com/sevginuroksuz/simple-item-manager.git
cd simple-item-manager
```

### Install Dependencies  
```sh
npm install
```

---

## Running the Application  

### Run with Docker  
To start all services using Docker:

```sh
docker-compose up -d
```

### Run Manually  
To run the application without Docker:

```sh
node server.js
```

You can access the application at **http://localhost:3000** 🎉

---

## Project Structure  

```plaintext
 simple-item-manager
 ├ 📂 src
 ┃ ├ 📄 server.js          # Main backend file
 ┃ ├ 📄 database.js        # MongoDB connection
 ┃ └ 📄 cache.js           # Redis integration
 ├ 📄 Dockerfile           # Docker configuration
 ├ 📄 docker-compose.yml   # Multi-container management
 ├ 📄 package.json         # Dependencies
 ├ 📄 README.md            # Project documentation (TR)
 ├ 📄 README.en.md         # Project documentation (EN)
 └ 📄 .gitignore           # Ignored files
```

---

## License  
This project is licensed under the **MIT License**.  
For more details, please check the [LICENSE](LICENSE) file.

---

**If you like this project, don’t forget to give it a ⭐!**
