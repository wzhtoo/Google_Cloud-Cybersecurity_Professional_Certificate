# 06_Graded App lItem_Createa VPC Using Cloud Shell

[Graded App lItem_Createa VPC Using Cloud Shell &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/gradedLti/gcWyj/create-a-vpc-using-cloud-shell)

# Create a VPC using Cloud Shell

Create and then view a VPC with a subnet.

## Tips for Course Labs

Get the most out of Coursera and Qwiklabs by trying our tips below.

### Avoid account confusion with private browsing

**Close this page and log back in to Coursera in Incognito mode** before moving on. When you return to this course and lab instructions page, click Launch App to continue.

By using incognito mode, this ensures that you don't accidentally use your own Google account (including Gmail) while accessing the Google Cloud Console. This also prevents Qwiklabs from logging you out of your own Google accounts.

Detailed instructions for using Incognito mode in Google Chrome are
available here Opens in a new tab
. Depending on your browser, Incognito mode might also be called Private Browsing or InPrivate Browsing.

### To ensure lab completion is marked in Coursera:

1. Access each individual lab by clicking Launch App in Coursera:

<button style="background-color: #005bd8; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer;">Launch App 🔗</button>

2. Complete the lab in Qwiklabs.

3. Click **End Lab** in Qwiklabs:

- student-01-04589c295f61@qwiklabs.net
- 6cvsGz2FxBN6
- qwiklabs-gcp-01-e248c76dcde3

Troubleshooting info:
Principal: wzhtoo@gmail.com
Resource: qwiklabs-gcp-01-e248c76dcde3
Troubleshooting URL: console.cloud.google.com/iam-admin/troubleshooter;permissions=resourcemanager.projects.get;principal=wzhtoo@gmail.com;resources=%2F%2Fcloudresourcemanager.googleapis.com%2Fprojects%2Fqwiklabs-gcp-01-e248c76dcde3/result

Missing permissions:
resourcemanager.projects.get

# Setp 1

```plaintext
NAME: labnet
SUBNET_MODE: CUSTOM
BGP_ROUTING_MODE: REGIONAL
IPV4_RANGE:
GATEWAY_IPV4:

Instances on this network will not be reachable until firewall rules
are created. As an example, you can allow all internal traffic between
instances as well as SSH, RDP, and ICMP by running:

$ gcloud compute firewall-rules create <FIREWALL_NAME> --network labnet --allow tcp,udp,icmp --source-ranges <IP_RANGE>
$ gcloud compute firewall-rules create <FIREWALL_NAME> --network labnet --allow tcp:22,tcp:3389,icmp
```

```plaintext
NAME: default
SUBNET_MODE: AUTO
BGP_ROUTING_MODE: REGIONAL
IPV4_RANGE:
GATEWAY_IPV4:

NAME: labnet
SUBNET_MODE: CUSTOM
BGP_ROUTING_MODE: REGIONAL
IPV4_RANGE:
GATEWAY_IPV4:
```

```plaintext
NAME: labnet-sub
REGION: us-east1
NETWORK: labnet
RANGE: 10.0.0.0/28
STACK_TYPE: IPV4_ONLY
IPV6_ACCESS_TYPE:
INTERNAL_IPV6_PREFIX:
EXTERNAL_IPV6_PREFIX:
```
