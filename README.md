# Ansible configurations for my mac laptop

Adapted from https://adamj.eu/tech/2019/03/20/how-i-provision-my-macbook-with-ansible/ and https://github.com/adamchainz/mac-ansible.

This mostly exists to keep my mac up-to-date month to month, ensuring I'm applying the latest software updates.

As a side-effect, it's hopefully going to be quite nice for if I want to provision a new mac one day.

I used to keep this stuff in shellscripts, but shell-script error-handling is quite difficult to get correct, and ansible seems much higher-level and declarative, with structured output.

Prerequisites:

Install homebrew

```
python3 -m ensurepip
pip3 install ansible
```

To run:

```
./main.yml
```

To skip to a specific section:

```
./main.yml -t fish
```
