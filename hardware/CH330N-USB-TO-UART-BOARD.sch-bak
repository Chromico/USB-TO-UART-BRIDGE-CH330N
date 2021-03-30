EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Interface_USB:CH330N U1
U 1 1 5FB5B98C
P 5550 3550
F 0 "U1" H 5550 4031 50  0000 C CNN
F 1 "CH330N" H 5550 3940 50  0000 C CNN
F 2 "Package_SO:SOIC-8_3.9x4.9mm_P1.27mm" H 5400 4300 50  0001 C CNN
F 3 "http://www.wch.cn/downloads/file/240.html" H 5450 3750 50  0001 C CNN
	1    5550 3550
	1    0    0    -1  
$EndComp
$Comp
L Device:C C2
U 1 1 5FB5BCC3
P 4550 3600
F 0 "C2" H 4665 3646 50  0000 L CNN
F 1 "100nf" H 4665 3555 50  0000 L CNN
F 2 "" H 4588 3450 50  0001 C CNN
F 3 "~" H 4550 3600 50  0001 C CNN
	1    4550 3600
	1    0    0    -1  
$EndComp
$Comp
L Device:C C1
U 1 1 5FB5C0EB
P 3850 3550
F 0 "C1" H 3965 3596 50  0000 L CNN
F 1 "100nf" H 3965 3505 50  0000 L CNN
F 2 "" H 3888 3400 50  0001 C CNN
F 3 "~" H 3850 3550 50  0001 C CNN
	1    3850 3550
	1    0    0    -1  
$EndComp
$Comp
L Graphic:Logo_Open_Hardware_Small #LOGO1
U 1 1 5FB5E53D
P 7400 6850
F 0 "#LOGO1" H 7400 7125 50  0001 C CNN
F 1 "Logo_Open_Hardware_Small" H 7400 6625 50  0001 C CNN
F 2 "" H 7400 6850 50  0001 C CNN
F 3 "~" H 7400 6850 50  0001 C CNN
	1    7400 6850
	1    0    0    -1  
$EndComp
$Comp
L Device:LED D2
U 1 1 5FB5EBD2
P 5200 5000
F 0 "D2" H 5193 5217 50  0000 C CNN
F 1 "LED-RED" H 5193 5126 50  0000 C CNN
F 2 "" H 5200 5000 50  0001 C CNN
F 3 "~" H 5200 5000 50  0001 C CNN
	1    5200 5000
	1    0    0    -1  
$EndComp
$Comp
L Device:LED D1
U 1 1 5FB5F2CE
P 5200 4600
F 0 "D1" H 5193 4817 50  0000 C CNN
F 1 "LED-RED" H 5193 4726 50  0000 C CNN
F 2 "" H 5200 4600 50  0001 C CNN
F 3 "~" H 5200 4600 50  0001 C CNN
	1    5200 4600
	1    0    0    -1  
$EndComp
NoConn ~ 3500 3600
NoConn ~ 3500 3700
NoConn ~ 2600 4900
$Comp
L Connector:USB_C_Receptacle_USB2.0 J1
U 1 1 5FB62D60
P 2900 4000
F 0 "J1" H 3007 4867 50  0000 C CNN
F 1 "USB_C_Receptacle_USB2.0" H 3007 4776 50  0000 C CNN
F 2 "" H 3050 4000 50  0001 C CNN
F 3 "https://www.usb.org/sites/default/files/documents/usb_type-c.zip" H 3050 4000 50  0001 C CNN
	1    2900 4000
	1    0    0    -1  
$EndComp
Wire Wire Line
	3500 3900 3500 4000
Wire Wire Line
	3500 4100 3500 4150
NoConn ~ 3500 4500
NoConn ~ 3500 4600
Wire Wire Line
	3500 3400 3850 3400
Text Label 3850 3400 0    50   ~ 0
VBUS
$Comp
L power:GND #PWR0101
U 1 1 5FB661BF
P 3850 3700
F 0 "#PWR0101" H 3850 3450 50  0001 C CNN
F 1 "GND" H 3855 3527 50  0000 C CNN
F 2 "" H 3850 3700 50  0001 C CNN
F 3 "" H 3850 3700 50  0001 C CNN
	1    3850 3700
	1    0    0    -1  
$EndComp
Text Label 3600 4150 0    50   ~ 0
D+
Text Label 3600 4000 0    50   ~ 0
D-
Wire Wire Line
	3700 4000 3500 4000
Connection ~ 3500 4000
Wire Wire Line
	3700 4150 3500 4150
Connection ~ 3500 4150
Wire Wire Line
	3500 4150 3500 4200
$Comp
L power:GND #PWR0102
U 1 1 5FB68694
P 2900 4900
F 0 "#PWR0102" H 2900 4650 50  0001 C CNN
F 1 "GND" H 2905 4727 50  0000 C CNN
F 2 "" H 2900 4900 50  0001 C CNN
F 3 "" H 2900 4900 50  0001 C CNN
	1    2900 4900
	1    0    0    -1  
$EndComp
$Comp
L Connector_Generic_MountingPin:Conn_01x05_MountingPin J2
U 1 1 5FB69954
P 7300 3600
F 0 "J2" H 7388 3564 50  0000 L CNN
F 1 "Break-out-pins" H 7388 3473 50  0000 L CNN
F 2 "" H 7300 3600 50  0001 C CNN
F 3 "~" H 7300 3600 50  0001 C CNN
	1    7300 3600
	1    0    0    -1  
$EndComp
Text Label 5850 3250 0    50   ~ 0
VBUS
Wire Wire Line
	5550 3250 6050 3250
Text Label 6000 3450 0    50   ~ 0
TX
Text Label 6000 3550 0    50   ~ 0
RX
Text Label 6000 3750 0    50   ~ 0
RTS
$Comp
L power:GND #PWR0103
U 1 1 5FB6CD6A
P 5550 3950
F 0 "#PWR0103" H 5550 3700 50  0001 C CNN
F 1 "GND" H 5555 3777 50  0000 C CNN
F 2 "" H 5550 3950 50  0001 C CNN
F 3 "" H 5550 3950 50  0001 C CNN
	1    5550 3950
	1    0    0    -1  
$EndComp
Text Label 5000 3650 0    50   ~ 0
D+
Text Label 5000 3750 0    50   ~ 0
D-
Wire Wire Line
	6100 3450 5950 3450
Wire Wire Line
	6100 3550 5950 3550
Wire Wire Line
	6150 3750 5950 3750
Wire Wire Line
	5150 3650 5000 3650
Wire Wire Line
	5150 3750 5000 3750
Text Label 6800 3400 0    50   ~ 0
VBUS
$Comp
L power:GND #PWR0104
U 1 1 5FB73514
P 6900 3500
F 0 "#PWR0104" H 6900 3250 50  0001 C CNN
F 1 "GND" V 6905 3372 50  0000 R CNN
F 2 "" H 6900 3500 50  0001 C CNN
F 3 "" H 6900 3500 50  0001 C CNN
	1    6900 3500
	0    1    1    0   
$EndComp
Wire Wire Line
	7100 3400 6800 3400
Wire Wire Line
	7100 3500 6900 3500
Text Label 6900 3700 0    50   ~ 0
RX
Text Label 6900 3600 0    50   ~ 0
TX
Text Label 6900 3800 0    50   ~ 0
RTS
Wire Wire Line
	7100 3600 6900 3600
Wire Wire Line
	7100 3700 6900 3700
Wire Wire Line
	7100 3800 6900 3800
NoConn ~ 7300 4000
Text Notes 7350 7500 0    50   ~ 0
CH330N-USB-TO-UART-BOARD
Text Notes 10600 7650 0    50   ~ 0
1
Wire Wire Line
	5150 3450 4550 3450
$Comp
L power:GND #PWR0105
U 1 1 5FB772E1
P 4550 3750
F 0 "#PWR0105" H 4550 3500 50  0001 C CNN
F 1 "GND" H 4555 3577 50  0000 C CNN
F 2 "" H 4550 3750 50  0001 C CNN
F 3 "" H 4550 3750 50  0001 C CNN
	1    4550 3750
	1    0    0    -1  
$EndComp
$Comp
L Device:R R1
U 1 1 5FB7A0DC
P 5700 4600
F 0 "R1" V 5493 4600 50  0000 C CNN
F 1 "1K" V 5584 4600 50  0000 C CNN
F 2 "" V 5630 4600 50  0001 C CNN
F 3 "~" H 5700 4600 50  0001 C CNN
	1    5700 4600
	0    1    1    0   
$EndComp
$Comp
L Device:R R2
U 1 1 5FB7ABF9
P 5700 5000
F 0 "R2" V 5493 5000 50  0000 C CNN
F 1 "1K" V 5584 5000 50  0000 C CNN
F 2 "" V 5630 5000 50  0001 C CNN
F 3 "~" H 5700 5000 50  0001 C CNN
	1    5700 5000
	0    1    1    0   
$EndComp
Text Label 5950 4600 0    50   ~ 0
VBUS
Text Label 5950 5000 0    50   ~ 0
VBUS
Text Label 4800 4600 0    50   ~ 0
RX
Text Label 4800 5000 0    50   ~ 0
TX
Wire Wire Line
	6150 4600 5850 4600
Wire Wire Line
	6150 5000 5850 5000
Wire Wire Line
	5550 4600 5350 4600
Wire Wire Line
	5550 5000 5350 5000
Wire Wire Line
	5050 4600 4800 4600
Wire Wire Line
	5050 5000 4800 5000
$EndSCHEMATC
