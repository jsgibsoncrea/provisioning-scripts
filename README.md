# Provisioning Scripts
This repo is set up to house provisioning scripts for Vagrant VMs and maybe more.

## Requirements 

Because Windows is not compatible with Ansible (due to missing common tools included in other OS), running the scripts in WSL (1 or 2) is required.

Also required is the `community.general` collection from ansible-galaxy. If you install the `ansible` package rather than just  `ansible-core` it should be included, but you can check via `ansible-galaxy collection list` and install via `ansible-galaxy collection install community.general`