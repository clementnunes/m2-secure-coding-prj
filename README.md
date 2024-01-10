

# m2-secure-coding-app

## Overview

m2-secure-coding-prj is a project that aims to use CI/CD practises, for Secure Coding Module - Software Engineering @ EFREI.\
  
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

## Installation

Clone the Repository:
Open a terminal or command prompt and use the git clone command to clone the repository.

```
git clone https://github.com/clementnunes/m2-secure-coding-app
```

Navigate to the Project Directory:
Change your current directory to the one where the project has been cloned.

```
cd repository
```

## Usage
**Run manually**
```
docker network create "dbnet"
docker-compose -f docker-compose.monitoring.yml -p "m2-devops-prj-monitoring" up
docker-compose -f docker-compose.app.yml -p "m2-devops-prj-app" up
```

Or run scripts/build_monitoring.sh

## Features
Managing the lifecycle of the application:
- Build (Application and Database)
- Test
- Preprod and production
- Monitoring using Prometheus and Grafana

## Contact

**Clement Nunes**\
**clement.nunes@efrei.net**
