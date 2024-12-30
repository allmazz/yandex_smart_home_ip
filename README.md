# yandex_smart_home_ip
IPs(subnets) used by Yandex Home(Alice)
# Subnets
I wrote down all the addresses from which Yandex Home submitted requests. Then I checked through WHOIS the service to whom the IP belongs and the subnet.

```
allow 5.45.207.0/24;
allow 5.45.235.64/26;
allow 5.255.199.0/26;
allow 5.255.228.0/24;
allow 5.255.253.0/24;
allow 37.9.68.128/26;
allow 37.9.87.0/25;
allow 37.9.102.0/26;
allow 37.9.122.0/24;
allow 37.140.152.128/25;
allow 37.140.189.192/26;
allow 141.8.129.0/24;
allow 141.8.142.0/24;
```
## Mikrotik script
```
/ip firewall address-list add address=5.45.207.0/24 list=ya_home;
/ip firewall address-list add address=5.45.235.64/26 list=ya_home;
/ip firewall address-list add address=5.255.199.0/26 list=ya_home;
/ip firewall address-list add address=5.255.228.0/24 list=ya_home;
/ip firewall address-list add address=5.255.253.0/24 list=ya_home;
/ip firewall address-list add address=37.9.68.128/26 list=ya_home;
/ip firewall address-list add address=37.9.87.0/25 list=ya_home;
/ip firewall address-list add address=37.9.102.0/26 list=ya_home;
/ip firewall address-list add address=37.9.122.0/24 list=ya_home;
/ip firewall address-list add address=37.140.152.128/25 list=ya_home;
/ip firewall address-list add address=37.140.189.192/26 list=ya_home;
/ip firewall address-list add address=141.8.129.0/24 list=ya_home;
/ip firewall address-list add address=141.8.142.0/24 list=ya_home;
```
Google Home adresses: https://github.com/allmazz/google_home_ip
