# divice
UC team configuration device used in the field.
The first thing we need to establish is you have to make sure that you can simply reach the device you’re after. A simple icmp test would suffice.
ping pubic ip of edmarc or foigate.
Switch ip sould be 192.168.225.2 255.255.255.0 with the last octech incressing my one per device.


>>> from netmiko import ConnectHandler

Next we’ll provide the details of my device:

>>> platform = ‘cisco_ios’ # this is optional you don’t need to include the platform
>>> host = ‘192.168.123.2’
>>> username = ‘admin’
>>> password = ‘secretpassword’
>>> device = ConnectHandler(device_type=platform, ip=host, username=username, password=password)


http://www.cisco.com/wwl/export/crypto/tool/stqrg.htmlin the 
Who see this, I am working on develping instruction for Edmarc, Forigate, Aruba just like Cisco did in the above link.

Check out this URL on HP_Aruba link: https://github.com/aruba
