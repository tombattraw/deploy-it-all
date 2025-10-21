INTENT:
Use Packer to prepare ISOs, Terraform to deploy them to Proxmox, Proxmox scripts add any needed devices, and Ansible and Nix to configure them, all from a single command.

Roadmap:
1. Get Packer to install Nix and ssh keys on RHEL, Debian, and Arch derivatives
2. Develop Nix configs for a few basic roles
3. Get Terraform deployment to Proxmox working
4. Get Proxmox scripts functioning
5. Get last-minute configuration with Ansible working
6. Develop good way of coordinating all moving parts and organizing the config files
7. Profit

Progress:
None so far. Updates to trickle in over time.
