[InfluxDB](http://influxdb.org/) Output Plugin for [Logstash](http://logstash.net/)

The original code is located in https://github.com/anaray/logstash/blob/master/lib/logstash/outputs/influxdb.rb

Usage in logstash conf file
```
output { 
  influxdb{
      hostname => "localhost"     # string, default: "localhost"
      username => "root"     # string
      password => "root"     # string
      database => "mlogs"    # string
      series_name => "log_t_series"    #string
      time_field => "date_time"     # string (optional)
      time_precision => 's'     # string (optional)  
  }
}
```
