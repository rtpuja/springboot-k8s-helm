# Spring Boot + Kubernetes + Helm Example

## 🧱 Structure

- Spring Boot REST API
- Dockerfile
- Helm Chart for Kubernetes deployment

## 🛠 Build & Deploy

```bash
mvn clean package
docker build -t your-dockerhub-username/springboot-app:1.0 .
docker push your-dockerhub-username/springboot-app:1.0

helm install my-springboot-app ./helm-chart/springboot-app
```