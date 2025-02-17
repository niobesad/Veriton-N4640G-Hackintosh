# Acer Veriton N4640G

Hackintosh in Ventura 13.3 updated to 13.7.4<br/>
OpenCore 0.9.0 updated to 1.0.3
<br/>

 Acer veriton N4640G<br/>
 Core i5 6400 / 2.71 GHz <br/>
 Intel HD530 <br/>
 SSD M.2 SATA 256GB <br/>
 16GB of DDR4 2133Mhz RAM <br/>
 
# Whats work
 Everything besides whats not work
 
# Whats not work
 Can't wake after sleep, common problem for skylake,
 Temporary workaround : set never for display off in energy saver settings
 
# Notes 
 Please change MLB, SystemSerialNumber, SystemUUID into your own `config.plist`.

```xml
<dict>
    ...
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    ...
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    ...
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```

# ScreenShoot
 Ventura 13.3
![alt textt](https://github.com/niobesad/Veriton-N4640G/blob/main/Screenshot%202024-10-06%20at%2011.41.18.png?raw=true)
<br>
 Ventura 13.7.4
![alt textt](https://github.com/niobesad/Veriton-N4640G/blob/main/Screenshot%202025-02-17%20at%2022.08.12.png?raw=true)