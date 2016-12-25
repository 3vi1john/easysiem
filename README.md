# easysiem
Easysiem link and md5

#
1. Boot From CD and install.
2. Boot then run sudo /etc/setup-siem.sh and set static IP address.
3. run sudo systemctl start graylog-server.
4. Start sending logs to the ip address you assigned at port udp 514


Logging in
Default for snorby is port 80

http://"ip"

login is snorby@example.com

password snorby

Default for graylog is port 9000

http://"ip":9000

login is admin

password easysiem

