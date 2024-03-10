
Firstly install the image of the thingy named [openwrt-bcm27xx-bcm2712-rpi-5-squashfs-factory.img.gz](https://github.com/mj22226/openwrt/releases/download/bcm2712-6.1/openwrt-bcm27xx-bcm2712-rpi-5-squashfs-factory.img.gz)

Secondly install the latest version of rufus @ https://rufus.ie/en/ or install it V4.4 @ [`rufus-4.4.exe`](https://github.com/pbatard/rufus/releases/download/v4.4/rufus-4.4.exe)
Thirdly add the image that you have installed onto the SD Card.

-------------------------------------------------------------------------------

# Go to your preferred browser 

input the Private IP 192.168.1.1

or

(Optional) If 192.168.1.1 does not work you may do a scan on 192.168.0.0 to find the desired Private IP where your precious config panel is 
[Simple way] Just go on CMD(WIndows) or Terminal(Linux) and to either 
```bat
ipconfig
```
or 
```bash
ifconfig
```

And search Default Gateway![[image.png]]

-------------------------------------------------------------------------------------------------------------
After you have entered the Management Panel You will have a Login reminder Default User and Pass is (root)
User: root
Pass: root

-------------------------------------------------------------------------------

# Now onto the setup part!!!!

(Optional) If you want your raspberry pi to become a WIFI giver then go to the network dropdown then go to wireless after that you will see !
![[image 1.png]]
You go to the second one NOT radio0 then enable it and you are done opening wireless support for your precious homebrew router!

To add PPPoE go to Network dropdown click interface then click Add new then click on the select dropdown onto PPPoE then add your conection stuff after you are done with that edit the thing again inpput ur PPPoE user and pass then go to firewall thingy ![[Pasted image 20240310172555.png]] and Assign firewall-zone as WAN!
AND BOOM YOU ARE FINALLY DONE!!!!!!!

-------------------------------------------------------------------------------

# WPA/WPA2 Encryption How to basic!

At the Key thingy you will have to put your own password that your wireless connection will have.
(Optional) It's not just WPA/WPA2 you can you can have WPA3 too if you want! So whatever!

![[Pasted image 20240310174148.png]]

![[image 2.png]]
