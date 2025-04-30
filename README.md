# Java Web App Deployment with AWS CI?CD
## Introduction
<br>

## Technologies
Here's what I'm using for this project:

- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
- Key pairs, SSH connections, git, maven and java
- **VSCode**: For my IDE, I chose Visual studio code. It connects directlty to my development EC2 instance, making it easy to edit code and manage files in the cloud.
-**Github**: All my web app code is stored and versioned in the github repository.
-**[COMING SOON] AWS CodeArtifact**: Once it's rolled out, CodeArtifact will store my artifacts and dependencies, which is great for high avalibility and speeding up my project's build process.
-**[COMING SOON] AWS CodeBuild**: Onice its rolled out, CodeBuild will take over my build process. It'll complie the source code, run tests, and produce ready to deploy

## Setup

To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/lalaloopsi213/nextwork-web-project
```

2. Navigate to the project directory:
``` bash
cd nextwork-web-project
```

3. Install dependencies:
```bash
mvn install
```

## Contact
If you have questions or comments, please contact Lacey 
-[linkedin]{https://www.linkedin.com/in/lacey-crawford/}

<br>

## Conclusion

Thank you for exploring this project I'll continue to build this pipeline and apply my learings to future projects!