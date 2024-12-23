# 05_PracticeAssignment_Activity Quiz_Manage IaC with Terraform

[PracticeAssignment_Activity Quiz_Manage IaC with Terraform &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/assignment-submission/QW6JB/activity-quiz-manage-iac-with-terraform)

# Assignment

[Assignment &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/assignment-submission/QW6JB/activity-quiz-manage-iac-with-terraform/attempt)

1.  Question 1
    In the Terraform code, what cloud resource does the first resource block create?

- The virtual machine
- The subnetwork
- **The Virtual Private Cloud**
  - The first resource block creates a Virtual Private Cloud on Google’s network. To create the virtual machine, you must first create the compute network that the virtual machine can run on. In this case, the compute network is a Google Cloud Virtual Private Cloud.
- The location of the virtual machine

2. Question 2
   In the Terraform code, what does the third resource block define? Select two answers.

- **The virtual machine**
  - The virtual machine itself is defined and created in the third resource block.
- **The zone of the virtual machine**
  - The virtual machine’s zone is defined in the third resource block.
- The network IP range
- The subnetwork

3. Question 3
   How would you change the location of the virtual machine in the Terraform file? Select two answers.

- **Change the zone**
  - Zones are deployment areas within a region. You should run resources across the zones closest to customers. In this Terraform template, the region is “us-west1-a.” To change the location of the virtual machine, input a zone closer to Cymbal Bank’s customer base.
- Change the network IP range
- **Change the region**
  - A region is a collection of zones. In this Terraform template, the region is “us-west1.” To change the location of the virtual machine, input a different region to improve Cymbal Bank’s customer reach.
- Change the variable name

4. Question 4
   You are preparing a presentation for Cymbal Bank's leadership that explains how IaC can improve the security of virtual machines. Which of the following statements should you include in the presentation? Select all that apply.

- **IaC tools may offer the ability to scan the environment for configuration drift.**
  - You should explain to leadership that configuration drift can lead to vulnerabilities. Identifying and correcting drift using IaC tools reduces the potential attack surface.
- **\*C: IaC tools can help you detect invalid inputs in the build process.**
  - You should explain to leadership that IaC can help you detect invalid inputs in the build process. For example, if you have a variable such as “number_of_instances,” you can say that it must range from 1–10.
- **Automation ensures developers consistently use the same configuration settings for provisioning infrastructure.**
  - You should explain to leadership that automating the provisioning of infrastructure with code leaves little room for unintentional errors made by infrastructure developers. Even a small deviation in the source code could result in unwelcome bugs or other security problems
- IaC saves security checks for the final step of the development process.
