# CI/CD Pipeline Example

This repository demonstrates a simple CI/CD pipeline using **GitHub Actions**:

✔ Build a Docker image  
✔ Run basic tests  
✔ Push image to container registry  
✔ Deploy to Kubernetes / OpenShift  

This workflow is ideal for DevOps, Platform Engineering, and Cloud roles.

---

## 📁 Repository Structure

cicd-pipeline-example/
│── app/
│ └── app.py
│
│── Dockerfile
│── deployment.yaml
│── service.yaml
│── .github/
│ └── workflows/
│ └── deploy.yml
│
└── README.md


---

## 🚀 CI/CD Workflow (GitHub Actions)

1. On **push** to `main`:
   - Checkout code
   - Build Docker image
   - Run tests
   - Push image to registry (Docker Hub / Quay)
   - Deploy using `kubectl` or `oc`

---

## 👤 Author  
Adil — Linux, DevOps & Platform Engineer
