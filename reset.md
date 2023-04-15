I installed elasticsearch kibana and metricbeats locally and forgot my passwords.  Now What?

Step 1 - Reset Elastic password
```
cd /usr/share/elasticsearch/bin
./elasticsearch-reset-password -u elastic
# Reference https://www.elastic.co/guide/en/elasticsearch/reference/current/reset-password.html
```
