# DONATE

1. Ethereum : <pre>0xB0e6e6c379389bBB30fACD427e02d74d27ec0C78</pre>
2. Near Blockchain : <pre>xoreth.near</pre>
3. Mina Protocol : <pre>B62qiiBBXKN5CdgXv7wPkXxC1prdzQxwfaTMAi3isAeb9F7gCbzi5dU</pre>





# SEND SMS 

Send sms for gsm serial utils  wavecom/modempool device 
version : python2.7

###How To Use?

Deploy udev
```
# cp -r udev.d/gsm.rules /etc/udev/rules.d/ 
# udevadm trigger && sudo udevadm control --reload-rules
``` 

Install depends
> pip install -r requirements.txt

Usage 
Sending SMS
> python2.7 send.wjt /dev/gsmmd1 081375799611 "kirim pesan"


USSD Request
> python2.7 ussd.wjt /dev/gsmmd1 '*888#'


We will update this script for support Pyhton 3.*
