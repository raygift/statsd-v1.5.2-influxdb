# statsd-v1.5.2-influxdb
statsd-influxdb-backend for statsd v1.5.2

influxdb 0.11版本后不再支持json格式的http api write方式,

本js文件在 https://github.com/bernd/statsd-influxdb-backend 基础上，

使用line Protocol格式替换json格式进行influxdb的write操作
