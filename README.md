🚀 Deployed a Miniature Microservices CI/CD – GitOps Pipeline

End-to-end CI/CD GitOps pipeline, which acts as a miniature version of a real-world microservices deployment.

This setup demonstrates how modern applications move from code commit to Kubernetes production with automation, quality gates, and Git as the single source of truth.

🔹 Developers push code to GitHub
🔹 Jenkins triggers the CI pipeline automatically
🔹 SonarQube validates code quality and security
🔹 Docker packages the application into container images
🔹 Images are stored in a container registry
🔹 Kubernetes manifests are maintained in a GitOps deployment repo
🔹 Argo CD continuously syncs Git state with the cluster
🔹 Helm manages versioned and repeatable deployments
🔹 Kubernetes runs and scales the application
🔹 Traffic is routed through services/load balancer to pods

💡 Though simplified, this architecture mirrors real production microservices pipelines used in enterprises — covering CI, security checks, containerization, GitOps, and Kubernetes deployment.
