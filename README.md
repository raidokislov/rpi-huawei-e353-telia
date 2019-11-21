# rpi-huawei-e353-telia

required: <br />
$ sudo apt-get install ppp usb-modeswitch <br />
$ sudo curl https://raw.githubusercontent.com/raidokislov/rpi-huawei-e353-telia/master/rnet -o /etc/ppp/peers/rnet <br />
$ sudo curl https://raw.githubusercontent.com/raidokislov/rpi-huawei-e353-telia/master/umts.chat -o /etc/ppp/umts.chat <br />
$ sudo rm /etc/usb_modeswitch.conf <br />
$ sudo curl https://raw.githubusercontent.com/raidokislov/rpi-huawei-e353-telia/master/usb_modeswitch.conf -o /etc/usb_modeswitch.conf <br />
$ sudo usb_modeswitch -c /etc/usb_modeswitch.conf 
