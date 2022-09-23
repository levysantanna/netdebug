## Network Debug Tools Dockerfiles

You will see directories for different distributions.

Now:

- Fedora
- RHEL

Tools added on the images:

- bind-utils 
- nmap
- iptraf-ng
- net-tools
- telnet
- wget
- links


# Creating Image
```oc new-app --strategy=docker --image="registry.fedoraproject.org/fedora:latest" https://github.com/levysantanna/netdebug.git --context-dir=/Fedora/```

