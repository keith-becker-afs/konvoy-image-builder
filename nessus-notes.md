sudo rpm -ivh NessusAgent-10.3.1-es8.x86_64.rpm

sudo /bin/systemctl start nessusagent.service

sudo /opt/nessus_agent/sbin/nessuscli agent link --key=4e19c807e62a70185ff6d4b8e5a68c802c91fb2d2ff98b51233c9fadb5a16bda --groups="Linux" --host="3.30.77.36" --port=8834