# Jenkins Docker

## Jenkins Docker Compose Configuration
A Docker Compose setup for Jenkins using the Jenkins LTS image OR any specific version, with added SSH agent functionality for enhanced security.

Getting Started
Easily set up Jenkins with Docker using this repository's configuration. Customize the Jenkins version and port, then start building, testing, and deploying your projects seamlessly.

### Prerequisites
- Docker
- Docker Compose

### Usage
1. Clone the repository.
2. Customize variables in .env & docker-compose.yml (refer .env.sample).
3. Run docker-compose up -d.
4. Access Jenkins at http://localhost:{PORT}.
5. Unlock Jenkins using the provided password.
6. Follow the Jenkins setup wizard.

### Features
- Persist Jenkins data with the jenkins_home volume.
- Securely handle SSH keys with the included SSH agent service.

### Author
<h3>Vrushal Raut</h3>
<p align="left">
<a href="https://twitter.com/vrushalrt" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="vrushalrt" height="30" width="40" /></a>
<a href="https://linkedin.com/in/vrushalraut" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="vrushalraut" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/5368888" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="5368888" height="30" width="40" /></a>
</p>

### License
This project is licensed under the MIT License.
