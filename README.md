
# Netflix Clone DevOps Project

This project is a Netflix clone implemented using AWS infrastructure and DevOps practices to ensure efficient development, security, monitoring, and deployment processes.

## Project Overview

The Netflix clone utilizes the following components:
- **EC2 Instances:** Utilized 2 large instances and 2 medium instances for deployment.
- **Elastic IP:** Used to maintain a static IP for EC2 instances.
- **Jenkins Pipeline:** Implemented a comprehensive Jenkins pipeline for continuous integration and deployment.
- **Technologies:** Docker, Docker Hub, Trivy, Jenkins, Grafana, Prometheus, Node Exporter, AWS, SonarQube, OWASP, Movies Database API.

## DevOps Pipeline

### Jenkins Pipeline Steps
1. **Clean Workspace:** Clearing the workspace before initiating the build process.
2. **Git Clone:** Pulling the latest code from the repository.
3. **SonarQube Analysis:** Running code analysis using SonarQube for monitoring code quality.
4. **Dependency Installation:** Installing project dependencies.
5. **OWASP FS SAST Scan:** Performing security analysis using OWASP FindSecBugs.
6. **Trivy Scan:** Conducting vulnerability scanning using Trivy.
7. **Build and Push:** Building the application and pushing the Docker image to Docker Hub.
8. **Deploy Container:** Deploying the containerized application from Docker Hub.
9. **Email Notifications:** Sending email notifications for build success or failure.

### Monitoring and Security
- **Monitoring:** Utilized Prometheus, Grafana, and Node Exporter for monitoring infrastructure and application metrics.
- **Security:** Implemented SonarQube, Trivy, and OWASP FindSecBugs for ensuring code and container security.

### Additional Components
- **Movies Database API:** Integrated an external API for fetching movie data.

## Documentation and Visuals

### Included in the README:
- Jenkins Pipeline Image
- PDF Logs Snapshot
- Docker Hub Image
- Prometheus Screenshot
- Email Notification Screenshot
- Demo Video showcasing the entire process

