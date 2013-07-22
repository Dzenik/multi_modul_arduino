multi_modul_arduino

������ ���������� � ��������� �� �������-���������.
����� � ����� ������� 4 ������ ����������, ��������� �� LCD Nokia 1202, 
���� ���������� SPI � I2C, 2-� ���������� �����, ���� ���� ���������� � ��������� �������� ������.
���������� ��� LCD Nokia 1202 https://github.com/SerPanRC/LCD_Nokia1202_Arduino.git

������ �������� ��� �������� ���������� ����������, ������������ ���������� ��������� 8���. ��� ������ � ������� ���������� � ����
arduino-1.X.X\hardware\arduino\boards.txt �������� ��������� ������-

##############################################################

micro168pa.name= (3.3V, 8 int MHz) w/ ATmega168PA

micro168pa.upload.protocol=stk500
micro168pa.upload.maximum_size=14336
micro168pa.upload.speed=19200

micro168pa.bootloader.low_fuses=0xE2
micro168pa.bootloader.high_fuses=0xdd
micro168pa.bootloader.extended_fuses=0x00
micro168pa.bootloader.path=atmega
micro168pa.bootloader.file=ATmegaBOOT_168_pro_8MHz.hex
micro168pa.bootloader.unlock_bits=0x3F
micro168pa.bootloader.lock_bits=0x0F

micro168pa.build.mcu=atmega168p
micro168pa.build.f_cpu=8000000L
micro168pa.build.core=arduino

����� ����� �������� � ���� ������ ���� (3.3V, 8 int MHz) w/ ATmega168PA , �� � �������� � ��� �������� ���������� � ��� �������� �������.
������ ����������� ����� boards.txt ���� � ��������.

� ������� ����� ����������� ������� ��� ������, ���� �������� �����, ����� ������.
� ����� receiver_1_2Ghz ������������ ����� ��� ������� ��������� 
�� �������� 0,8-1,45Ghz c �������������� ������.

