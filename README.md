# Ansible Container - Webserver Demo
Demo for creating a webserver container configured with Apache2 and PHP5 using Ansible Container.
View the related blog post at [adamstraube.github.io](https://adamstraube.github.io/build-a-docker-stack-with-ansible-container/)

## Requirements

Check the blog post above

## Build & Run

Use Ansible Galaxy to download the project, then build and run:
```bash
ansible-container init adamstraube.ansible-container-webserver-demo
ansible-container build
ansible-container run
```

# License

MIT

# Author Information

Created 2018 by [Adam Straube](adamstraube.github.io)
