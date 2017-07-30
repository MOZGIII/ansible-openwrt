# OpenWRT/LEDE DDNS management

## Config

Sample:

```yaml
ddns_config:
  test:
     enabled: '0'
     service_name: 'namecheap.com'
     use_https: '1'
     domain: 'your-dynamic-domain.com'
     username: '@'
     password: '[your password]'
     ip_source: 'network'
     interface: 'wan'
     ip_network: 'wan'
     use_syslog: '2'
     use_logfile: '1'
```
