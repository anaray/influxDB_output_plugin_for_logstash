[InfluxDB](http://influxdb.org/) Output Plugin for [Logstash](http://logstash.net/)

The original code is located in https://github.com/anaray/logstash/blob/master/lib/logstash/outputs/influxdb.rb

Usage in logstash conf file
```
output { 
  influxdb{
      username => "root"
      password => "root"
      database => "mlogs"
      series_name => "log_t_series"
  }
}
```
