FROM fedora:latest

USER root
RUN dnf install -y nc bind-utils nmap iptraf-ng net-tools telnet wget links; chpasswd root:netdebug

EXPOSE 9999
CMD ["nc", "-l", "-p", "9999", "-c", "echo hello"]
