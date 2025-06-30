# tvheadend
tvheadend firmware
Xbox One

```
mkdir /tmp/xboxone
cd /tmp/xboxone

https://github.com/zangaby/tvheadend/blob/main/xbox-one/dvb-demod-mn88472-02.fw
https://github.com/zangaby/tvheadend/blob/main/xbox-one/dvb-usb-dib0700-1.20.fw

sudo cp *.fw /lib/firmware
reboot
```

Hauppauge WinTV-dualHD
```
mkdir /tmp/hauppauge
cd /tmp/hauppauge

https://github.com/zangaby/tvheadend/blob/main/hauppauge-wintv-dualhd/dvb-demod-si2168-02.fw
https://github.com/zangaby/tvheadend/blob/main/hauppauge-wintv-dualhd/dvb-demod-si2168-b40-01.fw

sudo cp *.fw /lib/firmware
reboot
```
