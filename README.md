Informed by instructions here: http://sirlagz.net/2012/08/09/how-to-use-the-raspberry-pi-as-a-wireless-access-pointrouter-part-1/

Edit ConfigureMe.sh to set important values, such as AP ssid, passphrase, and channel.

Make sure you're at a real Raspi terminal - ssh will be cut off by this, in theory.

sudo /path/to/raspiwap.sh. 

ConfigureMe.sh should be kept in the same directory so the variables can be included.

TO DO: backup files that are changed and be able to restore to undo the changes.


