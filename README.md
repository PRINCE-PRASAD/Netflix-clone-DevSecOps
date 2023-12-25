
# Netflix Clone (DevOps Edition)

This project is a Netflix clone implemented using AWS infrastructure and DevOps practices to ensure efficient development, security, monitoring, and deployment processes.

![Netflix-clone-Live-Preview](./Assets/Netflix-clone-demo16mb.gif)

## Project Live Preview

![Netflix-clone-Live-Preview](./Assets/Netflix-clone-demo15mb.gif)

**OR**

Ready to experience it live? Check out the demo video: [Youtube video](https://youtu.be/JM7wsQt9ihI)

## Project Overview 

The Netflix clone utilizes the following components:
- **AWS Infrastructure:** Relies on EC2 instances (1 large, 1 medium) and Elastic IPs for flexibility and scalability.
- **Jenkins Pipeline:** Implemented a comprehensive Jenkins pipeline for continuous integration and deployment.
- **Technology Stack:** Docker, Docker Hub, Trivy, Jenkins, Grafana, Prometheus, Node Exporter, AWS, SonarQube, OWASP, Movies Database API.

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
- **Proactive Monitoring:** Grafana, Prometheus, and Node Exporter provide real-time insights into infrastructure and application health.
- **Comprehensive Security:** SonarQube, Trivy, and OWASP FindSecBugs safeguard code and container integrity.

### Additional Features
- **Movies Database API:** Integrated an external API for fetching movie data.

## Documentation and Visuals

### EC2 instance
<div align="center">
  <img src="./Assets/Screenshot (167).png" alt="Logo" width="100%" height="100%">
  <br>
    <img src="./Assets/Screenshot (165).png" alt="Logo" width="100%" height="100%">
</div>

### Jenkins Pipline Image
<div align="center">
  <img src="./Assets/Screenshot (177).png" alt="Logo" width="100%" height="100%">
</div>

### SonarQube Analysis Screenshot
<div align="center">
  <img src="./Assets/Screenshot (171).png" alt="Logo" width="100%" height="100%">
  </div>

### DockerHub Screenshot 
<div align="center">
  <img src="./Assets/Screenshot (164).png" alt="Logo" width="100%" height="100%">
  </div>

### Prometheus Screenshot
<div align="center">
  <img src="./Assets/Screenshot (168).png" alt="Logo" width="100%" height="100%">
  </div>

### Grafana Screenshot
<div align="center">
  <img src="./Assets/Screenshot (170).png" alt="Logo" width="100%" height="100%">
  <br>
    <img src="./Assets/Screenshot (169).png" alt="Logo" width="100%" height="100%">
</div>

### Email Notification Screenshot
<div align="center">
  <img src="./Assets/Screenshot (180).png" alt="Logo" width="100%" height="100%">
  <br>
    <img src="./Assets/Screenshot (181).png" alt="Logo" width="100%" height="100%">
</div>

## About Me

I'm a passionate developer driven by Full Stack Web Development, Cloud and DevOps Technologies, and solving problems through software innovation. Let's connect!

## Let's Connect
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prince-prasad/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/PRINCE__PRASAD)
[![github](https://img.shields.io/badge/github-3d4653?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PRINCE-PRASAD)
