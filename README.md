# DCM - Docker Container Monitor - pstambaugh14/DCM-Docker-Container-Monitor

The idea of this project is to enable an IT professional to monitor all running Docker containers in real-time with indexing, searches, graphs, statistics, and a beautiful web-UI to provide for all of your container-level analytics and monitoring needs.

TECHNOLOGIES TO BE UTILZIED:
- Google Kubernetes/Minikube
- Jenkins Docker Image
- Docker
- Containerd
- Ansible
- YAML & BASH
- Linux
- Elastic Technologies

## Credits

- Please check: 'https://github.com/pstambaugh14/DCM-Docker-Container-Monitor'

# Overview
- View your container's logs in real time.
- Monitor container-level system resources in real time.
- Index Data for analytics and machine learning
- Search Tools
- Graphs, statistics, Web-UI
- Beautiful Dashboard

# New Goals:
0) Convert Docker Daemon running on UNIX Sockets to tcp://0.0.0.0/:<docker_daemon_port>
1) All Docker Containers - This must first be discovered how to do in the best fashion possible.
	- BASH and Docker tools to communicate with API via Docker Commands
	- Ansible - Built-in modules to communicate with Docker API
	- Bash itself to use curl and whatnot to communicate with Docker API
2) Find a way to sidecar in just Docker (--net container:?).
3) Incorperate into TopBeat, ElasticSearch, Kibana
4) Integrate into Kubernetes
5) Write a Jenkins CI/CD Pipeline for the project (deployment into Kubernetes).

-----------------------------------------------------------------------------------------------------------------------------

# Overall Goal of This Project
- To provide live monitoring and analytics for use between Developers, Project Mangers, Administrators, Engineers, and everyone in-between.


# Credits:
Credits to licenses, person(s) involved, due credit to open-source providers or any other contributor.  
IBM/RedHat
Alphabet/Google
Oracle/Jenkins
Linus Torvalds
GNU
Elastic
MIT, APACHE, etc. Other Credits due probably.

## License
Created by Patrick Stambaugh.
https://github.com/pstambaugh14/DCM-Docker-Container-Monitor

## INSTALL INSTRUCTIONS
```sh
#Type this into your terminal to git clone the project directly onto your machine:
git clone https://github.com/pstambaugh14/DCM-Docker-Container-Monitor
```

## Configuration
Ansible: 

Requirements

The below requirements are needed on the host that executes this module.

    Docker API >= 1.20
    Docker SDK for Python: Please note that the docker-py Python module has been superseded by docker (see here for details). For Python 2.6, docker-py must be used. Otherwise, it is recommended to install the docker Python module. Note that both modules should not be installed at the same time. Also note that when both modules are installed and one of them is uninstalled, the other might no longer function and a reinstall of it is required.
    Docker SDK for Python >= 1.8.0 (use docker-py for Python 2.6)

## Quick Start
n/a

## ADVANCED/MORE DETAILED INFORMATION ON INSTALL, CONFIGS, ISSUES, BUGS, DEPLOYMENT, STARTUP, ETC.
n/a

## ADDITIONAL INFO:

```
#MORE INFO TO COME SOON!
```

