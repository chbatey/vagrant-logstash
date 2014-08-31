Run vagrant up

Fowards the following ports:
* Port 9200 - eastic search
* Port 5000 - lumberjack port in case you want to forward logs from another machine
* Port 4567 - Forwards to port 80, for the Kibana UI


By default the following runs on the VM:
* Elastic search
* Kibana inside Nginx
* Logstash
* Logstash forwarder forwarding its own logs to logstash
