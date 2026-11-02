# Terraform RKE2 Infrastructure

Infrastructure as Code project for provisioning a two-node
RKE2 Kubernetes cluster using Terraform, KVM, Libvirt, and Ansible.

## Architecture

- 1 RKE2 Server node
- 1 RKE2 Agent node
- Ubuntu Server 22.04
- Terraform for infrastructure provisioning
- Ansible for configuration management
- KVM/QEMU/Libvirt for virtualization
