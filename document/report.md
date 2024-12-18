{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2-1 What are testcontainers?\n",
    "Testcontainers is a Java library used to execute Docker containers. In this TP, we can see its usage in the pom.xml file.\n",
    "\n",
    "2-2 Document your GitHub Actions configurations\n",
    "GitHub Actions configurations define a CI/CD pipeline. These configurations are stored in the .github/workflows directory. They allow us to test, compile, and publish the Docker image.\n",
    "\n",
    "For what purpose do we need to push Docker images?\n",
    "We push the Docker image to create a registry on Docker Hub. This allows us to deploy the solution later in a consistent and reproducible environment.\n",
    "\n",
    "Document your quality gate configuration\n",
    "The quality gate in SonarCloud ensures code quality.\n",
    "We use Maven to execute Java code, verify to test Maven, and sonar:sonar to execute the Sonar plugin and check the code.\n",
    "\n",
    "Dsonar.projectKey: Identifies the project on SonarCloud.\n",
    "Dsonar.organization: Identifies the organization.\n",
    "Dsonar.login: Allows us to authenticate and connect to SonarCloud.\n",
    "3-1 Document your inventory and base commands\n",
    "The Ansible inventory file (inventories/setup.yml) is used to define the hosts for deployment.\n",
    "It allows us to connect to the hosts and test connectivity with a ping command.\n",
    "\n",
    "3-2 Document your playbook\n",
    "The playbook installs Docker on the remote server, creates a Docker network, and configures the PostgreSQL database container. Finally, it configures and starts the HTTPD proxy container.\n",
    "\n"
   ]
  }
 ],
 "metadata": {
  "language_info": {
   "name": "python"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
