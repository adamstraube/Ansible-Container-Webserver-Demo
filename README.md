# Ansible Container - Webserver Demo
Demo for creating a webserver container configured with Apache2 and PHP5 using Ansible Container.
View the related blog post at [adamstraube.github.io](https://adamstraube.github.io/build-a-docker-stack-with-ansible-container/)

## Requirements

Check the blog post above

## Build & Run

Use Ansible Galaxy to download the project, then build and run:

(note: Namespace id required currently in init command. Will change back when https://github.com/ansible/ansible-container-demo/issues/7 is fixed)
```bash
ansible-container init 1327.Ansible-Container-Webserver-Demo
ansible-container build
ansible-container run
```

# License

MIT

# Author Information

Created 2018 by [Adam Straube](adamstraube.github.io)
