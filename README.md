# Basic-Docker-and-Git-commands

Welcome to the Basic-Docker-and-Git-commands repository! This repository provides a basic understanding and implementation of Docker and Git commands, along with GitHub Actions for automation.

## Table of Contents
- [Introduction](#introduction)
- [Commands Covered](#commands-covered)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction
This repository serves as a beginner's guide to using Docker and Git commands effectively. It covers essential commands for Docker, such as creating Docker images, publishing them to Docker Hub, and integrating with GitHub Actions for continuous integration and deployment.

## Commands Covered
1. **Create the Image**: Details on creating Docker images using a `Dockerfile`.
2. **Publish the Image to Docker Hub**: Steps to push Docker images to Docker Hub for distribution.
3. **GitHub Actions**: Example workflows (`docker-image.yml` and `pushImageToGithub.yml`) demonstrating how to automate Docker image builds and pushes using GitHub Actions.

## Technologies Used
- **Docker**: Containerization platform used to package and run applications.
- **GitHub Actions**: CI/CD platform used for automating workflows.
- **Git**: Version control system for tracking changes in code.

## File Structure
```
Basic-Docker-and-Git-commands/
│
├── .github/workflows/
│   ├── docker-image.yml          # GitHub Actions workflow for building Docker images
│   └── pushImageToGithub.yml     # GitHub Actions workflow for pushing Docker images to GitHub
│
├── Dockerfile                    # Dockerfile for building the Docker image
├── README.md                     # This README file
└── package.json                  # Example file (can be ignored)
```

## Usage
This repository can be used as a reference guide for learning and practicing Docker and Git commands. Follow the steps in the `README.md` file and explore the provided workflows (`docker-image.yml` and `pushImageToGithub.yml`) to understand how Docker images can be built, published, and integrated into automated workflows using GitHub Actions.

## Contributing
Contributions are welcome! If you have any improvements or additional commands to suggest, please fork this repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact
**Divya Soni**
- [Email](mailto:sonidivya018@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/divya-soni-311777229/)

Feel free to contact me if you have any questions or feedback regarding the project.

---

Happy coding with Docker and Git! 🐳
