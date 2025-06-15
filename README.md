# IBM Node App with Docker

This is a simple Node.js application containerized using Docker and pushed to the IBM Cloud Container Registry. It demonstrates basic DevOps skills including Dockerfile creation, image building, and cloud registry integration.

---

## 🚀 Features

- Simple Node.js HTTP server
- Dockerized with a production-ready Dockerfile
- Tagged and pushed to IBM Cloud Container Registry
- Clean folder structure and logs

---

## 📦 Technologies Used

- Node.js
- Docker
- IBM Cloud CLI
- IBM Container Registry

---

## 📁 Folder Structure

/Dockerfile
/index.js or app.js
/package.json


---

## 🐳 Run Locally Using Docker

```bash
# Build the image
docker build -t ibm-node-app .

# Run the container
docker run -p 3000:3000 ibm-node-app

Open http://localhost:3000 in your browser.


☁️ IBM Cloud Push Commands

# Tag the image
docker tag ibm-node-app us.icr.io/sufian-k8s-registry-dallas/ibm-node-app:v1

# Push to IBM registry
docker push us.icr.io/sufian-k8s-registry-dallas/ibm-node-app:v1

🧠 What I Learned
How to containerize a Node.js app using Docker

How to push Docker images to IBM Cloud Container Registry

Hands-on experience with IBM Cloud CLI and container namespaces

