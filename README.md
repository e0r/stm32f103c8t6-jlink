NEWEST FIRMWARE:J-Link OB-STM32F103 V1 compiled Apr  8 2020 10:10:28

BUT THIS ASSHOLE FIRMWARE HAD LIMITED THE SPEED AT 2000KHZ.

THIS IS ASSHOLE.BIN

Had used the st-link bootloader from this:
                                      https://github.com/Krakenw/Stlink-Bootloaders
# stm32f103c8t6-jlink
C8T6核心板JLINK固件<br>
the bibi.bin is   FW:J-Link STLink V2 compiled Jun 26 2017 10:34:41,  this version can be reflashed to stlink or update the j-link fw.<br>
the bibi21.bin is FW:J-Link STLink V21 compiled Jun 26 2017 10:35:16，while this one cannot!<br>
Target interface speed: 4000 kHz (Fixed)
![image](https://github.com/e0r/stm32f103c8t6-jlink/blob/master/pic/jlink2.JPG)<br>
![image](https://github.com/e0r/stm32f103c8t6-jlink/blob/master/pic/link.JPG)<br>
![image](https://github.com/e0r/stm32f103c8t6-jlink/blob/master/pic/jlink21.JPG)<br>
追求完美就加三个电阻，实际上CLK时钟直接接PB13,DIO数据直接接PB14也一点问题都没有。不过可能不太稳定。<br>
带c的去除了坑爹的许可证条款。<br>
（Files named including 'c' had been remove the daddy-fucking permission terms）<br>
