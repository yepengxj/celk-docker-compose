FROM  index.alauda.cn/library/logstash:latest

ADD logstash.conf /etc/logstash/conf.d/logstash.conf
RUN logstash agent -f /etc/logstash/conf.d/logstash.conf
