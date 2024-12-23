# 04_Reading_Activity_Manage IaC with Terraform

[Reading_Activity_Manage IaC with Terraform &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/supplement/1ecvs/activity-manage-iac-with-terraform)

[Activity_Manage IaC with Terraform.pdf](https://1drv.ms/b/c/526c45566c8c239a/Ecejcji2P9dFngeSH7etpDgBzrLG2caK2zRs-_4Yz_na1w?e=UpcYdC)

```Unset
resource "google_compute_network" "vpc_network" {
name = "my-custom-mode-network"
auto_create_subnetworks = false
mtu = 1460
}
resource "google_compute_subnetwork" "default" {
name = "my-custom-subnet"
ip_cidr_range = "10.0.1.0/24"
region = "us-west1"
network = google_compute_network.vpc_network.id
}
# Create a single Compute Engine instance
resource "google_compute_instance" "default" {
name = "flask-vm"
machine_type = "f1-micro"
zone = "us-west1-a"
tags = ["ssh"]
boot_disk {
initialize_params {
image = "debian-cloud/debian-11"
}
}
# Install Flask
metadata_startup_script = "sudo apt-get update; sudo apt-get
install -yq build-essential python3-pip rsync; pip install flask"
network_interface {
subnetwork = google_compute_subnetwork.default.id
access_config {
# Include this section to give the VM an external IP address
}
}
}
```
