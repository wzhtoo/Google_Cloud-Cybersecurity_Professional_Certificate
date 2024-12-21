# 04_PracticeAssignment_Test Your Knowledge Identity And Access Management(IAM)

[PracticeAssignment_Test Your Knowledge Identity And Access Management(IAM) &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/assignment-submission/ptA9D/test-your-knowledge-identity-and-access-management-iam)

# Assignment details

[Assignment details &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/assignment-submission/ptA9D/test-your-knowledge-identity-and-access-management-iam/attempt)

1.  Question 1
    A consultant needs to simply demonstrate the principle of least privilege to a client. Which of the following examples should the consultant use to demonstrate the principle of least privilege?

- Granting a temporary administrative employee access to all of the organization’s resources
- Creating a group to bind multiple users to a role
- **Granting a service account an identity and access management (IAM) role to perform a certain action only**
  - Following the principle of least privilege involves granting only the minimal access and authorization required to complete a task or function.
- Setting an employee’s access to expire at the end of a calendar year
- Granting the same access to all members of an organization

2. Question 2
   What is the term for a method of granting users and service accounts access to a cloud environment using IAM?

- Principals
- Allow policies
- **Federation**
  - Federation is a method of granting users and service accounts access to a cloud environment using IAM. Federation is also used to authenticate users external to an organization.
- Least privilege

3. Question 3
   What is the term for a non-human identity that is typically granted to a virtual machine, application, or service?

- Principal
- **Service account**
  - A service account is a non-human identity that is typically granted to a virtual machine, application, or service. Service accounts are granted IAM roles to perform certain actions.
- Infrastructure as a service (IaaS)
- Role

4. Question 4
   You are configuring IAM policies for your employer. Your development team consists of 10 people who will all need access to the same few storage buckets and virtual machines within your cloud environment. How can you most effectively accomplish this objective?

- Create a service account for the team, then assign the service account a role with the needed permissions.
- Create a service account for the team, then bind the account to a role with access to your entire cloud environment.
- **Create a group for the team members, then use an allow policy to bind the group to a role that has the needed permissions.**
  - To give permissions to an entire team of users, create a group for the team members, then use an allow policy to bind the group to a role that has the permissions needed. Assigning the correct roles and policies helps organizations enforce separation of duties so that users do not have levels of authorization that would allow them to misuse the system.
- Create a group for the team members, then individually assign each group member the needed permissions.
