# 09_Test your knowledge: Orchestrators and security of containers

[Test your knowledge: Orchestrators and security of containers 🔗](https://www.coursera.org/learn/cloud-security-risks-identify-and-protect-against-threats/assignment-submission/IOCKZ/test-your-knowledge-orchestrators-and-security-of-containers)

## Assignment

[Assignment 🔗](https://www.coursera.org/learn/cloud-security-risks-identify-and-protect-against-threats/assignment-submission/IOCKZ/test-your-knowledge-orchestrators-and-security-of-containers/attempt)

1.  Question 1
    What is the purpose of namespaces in container clusters? Select two answers.

- To grant necessary privileges for the task
- **To isolate applications in container clusters**
  - Namespaces are used to group services for applications and isolate applications in container clusters.
- To enforce role-based access controls
- To group services for applications
  - Namespaces are used to group services for applications and isolate applications in container clusters.
- To remove vulnerabilities from deployments

2. Question 2
   A company uses container images for its applications. To prevent container drift, they want to implement a strategy that ensures no new executables can be added after the container image has been created. Which option should the company use to prevent container drift?

- Implement a versioning mechanism.
- Allow unrestricted writing to the container layer.
- Keep a backup of the original image.
- **Make the container immutable.**
  - Making the container immutable prevents drift by ensuring no new executables can be added, stopping potential drift.

3. Question 3
   Which programming approach does orchestration utilize?

- Functional programming
- Sequential programming
- **Declarative programming**
  - Orchestration uses declarative programming to define the desired outcome of an automation.
- Object-oriented programming

  4.  Question 4
      A national company experiences an unexpected power outage at one of its data centers. In this context, what major function does the company’s container orchestration tool perform during the outage?

- Stops the system
- Activates an alarm
- Monitors the situation without acting
- **Moves containers to other hosts**
  - During an unexpected outage, container orchestration tools move containers to other hosts. This ensures that the application remains up and running, maintaining its health and performance.

5. Question 5
   During a deployment at an e-commerce tech startup, orchestration abruptly halts the deployment process. In this scenario, which is the most likely reason for the stop?

- **A policy violation due to container vulnerabilities**
  - The orchestration process stops deployment when a container has vulnerabilities that violate a policy. This is to avoid human error and ensure safe deployment.
- A request from the developers
- A random check for system resiliency
- A disk space error in a container
