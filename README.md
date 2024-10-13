# TLC SYS-IO for MECB

This board consists of the following:

- SCC2691 ACIA

- WDC6522N

- RTC72421 - with battery backup

- ATTINY261A-P -for PS/2 Keyboard

I have brought out all available outputs along the top of the PCB, however, the PS/2 clock and data signals are also on the connector (pins C11 and A12 repectively) as are TxD (A16), RxD (A17), RTS (C16) and CTS (C19).

Use at your own risk as I have not had time yet to fully test the PCB. 

Also, the battery holder is an SMD part. It's easy enough to attach, I used a heat gun from underneath the pcb.

UPDATES

1.3 - Fixed Reset line on SCC2691, updated battery holder.

1.4 - Fixed KYBD clk line.
