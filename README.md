# usbgaget
dhcp.conf
```
option domain-name-servers 8.8.8.8, 8.8.4.4;
option subnet-mask 255.255.255.0;
subnet 172.16.44.0 netmask 255.255.255.0 {
  range 172.16.43.2 172.16.44.254;
}
```
note
```
/sys/kernel/config/usb_gadget/g1/idProduct
0xd001

/sys/kernel/config/usb_gadget/g1/idVendor
0x18d1

/sys/kernel/config/usb_gadget
CONFIGFS

$CONFIGFS/g1/functions/usb_network_function
rndis.usb0
``` 
