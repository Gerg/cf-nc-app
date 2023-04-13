---
web: while true; do { echo -e 'HTTP/1.1 200 OK\r\n'; echo -e "$(cat /etc/lsb-release)"; } | nc -q 1 -l $PORT; done
