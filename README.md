# IREC2018-ESP-code

Telem CONOPS:

Skybass is an AP and a STA. It receives /arm, /disarm. When it receives a 0xAA / 0xAB byte over radio, it requests arming/disarming payload. IP: 192.168.4.1.

Payload is a STA, and connects to Skybass AP. It receives /arm, /disarm. If skybass doesn't exist, it turns to an AP and makes it own wifi to allow /arm, /disarm. IP: 192.168.4.2. 

Motherboard is an AP, and receives /arm, /disarm. IP: 192.168.4.1