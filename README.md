# Auto-Network-Sensor
Lightweight IDS sensor designed to send logs to the Elastic Stack

The Auto-Network-Sensor(ANS) is a small platform network monitoring device that utilizes both Zeek and Suricata. The logs of both services are then shipped to Elasticsearch via filebeat. In addition auditbeat and metricbeat send vital information about the sensor itself for security and operational purposes. This project is highly inspired by the work of the team that made RockNSM(https://github.com/rocknsm). The ANS was developed to meet the needs of smaller hardware requirments and the utilization of Ubuntu(or other Debian based) OS. The other goal of the project is to ship the logs directly using beats versus employing Logstash. 
