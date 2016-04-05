FROM  index.alauda.cn/library/logstash:latest

ADD logstash.conf /etc/logstash/conf.d/logstash.conf
#ADD key /etc/logstash/conf.d/key
#ADD cert /etc/logstash/conf.d/cert
CMD logstash  -f /etc/logstash/conf.d/logstash.conf
