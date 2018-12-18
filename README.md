# Docker Parallel

Run cmd in parallel against multiple Docker images.

## Usage

Try install a package on all platforms:

    ./mail.yml -e package=python3-dev

Limit to ubuntu distros:

    ./mail.yml -e package=python3-dev --limit ubuntu
