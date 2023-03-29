# Acer Veriton N4640G

Hackintosh in Monterey 12.6.4 <br/>
<br/>

 Acer veriton N4640G<br/>
 Core i5 6400 / 2.71 GHz <br/>
 Intel HD530 <br/>
 SSD M.2 SATA 256GB <br/>
 16GB of DDR4 2133Mhz RAM <br/>
 
# Whats work
 Everything besides whats not work
 
# Whats not work
 Can't wake after sleep, common problem for skylake
 set never for display off in energy saver settings
 
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
![alt textt](https://github.com/niobesad/Veriton-N4640G/blob/main/Screen%20Shot%202023-03-30%20at%2012.45.17%20AM.png?raw=true)
