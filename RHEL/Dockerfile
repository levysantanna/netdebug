FROM rhel7:latest

USER root
RUN yum install -y bind-utils nmap iptraf-ng net-tools telnet wget links nc iperf3 ; chpasswd root:netdebug

EXPOSE 9999
CMD ["nc", "-l", "-p", "9999", "-c", "echo hello"]
