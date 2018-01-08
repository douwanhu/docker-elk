# dockerized elk stack


[elk](http://www.elasticsearch.org/overview/) 是整合了elasticsearch logstash kibana的日志处理系统<br>
针对海量日志数据进行搜索归类并支持定制成可视dashboard。多蜜罐系统集成此系统统计威胁数据，出具可视化<br>
报告，对elasticsearch-2.4.1 logstash-2.4.0_all kibana-4.6.2-amd64制作docker镜像，定制了UI界面、可视化视图<br>
和各个蜜罐独立的dashboard。可以通过修改配置实现与第三方SIEM系统的对接。<br>
# Multi-Honeypots Dashboard

![Multi-Honeypots Dashboard](https://raw.githubusercontent.com/dtag-dev-sec/elk/master/doc/dashboard.png)
