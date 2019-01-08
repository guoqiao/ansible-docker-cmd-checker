# Ansible Docker Parallel

Run cmd in parallel against multiple Docker images with Ansible.

## Usage

Try install a package on all platforms:

    ./main.yml -e package=python3-dev

Limit to ubuntu distros:

    ./main.yml -e package=python3-dev --limit ubuntu
