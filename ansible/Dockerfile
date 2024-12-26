# Dockerfile
FROM python:3.9-slim

# Install dependencies
RUN apt-get update && apt-get install -y \
    sshpass \
    openssh-client \
    && rm -rf /var/lib/apt/lists/*

# Install Ansible
RUN pip install ansible

# Create a directory for Ansible playbooks
WORKDIR /ansible

# Set up the entry point for Ansible commands
ENTRYPOINT ["ansible-playbook"]
