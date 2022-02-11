# crc

```
//El valor CHECK es el resultado de realizar el calculo CRC para el char[] = "123456789";
//The CHECK value is the result of making the checksum of the char[] = "123456789";
/*
 * Valores sacados de la pagina http://crcmod.sourceforge.net/crcmod.predefined.html Es posible que alguno este mal.
 * This values have been taken from http://crcmod.sourceforge.net/crcmod.predefined.html some of them could be wrong
 Name                   Polynomial              Reversed?   Init-value	        XOR-out	                Check
crc-8                   0x07                    False       0x00	        0x00	                0xF4
crc-8-darc              0x39	                True        0x00	        0x00	                0x15
crc-8-i-code            0x1D	                False       0xFD	        0x00	                0x7E
crc-8-itu               0x07	                False       0x55	        0x55	                0xA1
crc-8-maxim             0x131	                True        0x00	        0x00	                0xA1
crc-8-rohc              0x07	                True        0xFF	        0x00	                0xD0
crc-8-wcdma             0x9B	                True        0x00	        0x00	                0x25
crc-16                  0x8005	                True        0x0000	        0x0000	                0xBB3D
crc-16-buypass          0x8005	                False       0x0000	        0x0000	                0xFEE8
crc-16-dds-110          0x8005	                False       0x800D	        0x0000	                0x9ECF
crc-16-dect             0x0589	                False       0x0001	        0x0001	                0x007E
crc-16-dnp              0x3D65	                True        0xFFFF	        0xFFFF	                0xEA82
crc-16-en-13757         0x3D65	                False       0xFFFF	        0xFFFF	                0xC2B7
crc-16-genibus          0x1021	                False       0x0000	        0xFFFF	                0xD64E
crc-16-maxim            0x8005	                True        0xFFFF	        0xFFFF	                0x44C2
crc-16-mcrf4xx          0x1021	                True        0xFFFF	        0x0000	                0x6F91
crc-16-riello           0x1021	                True        0x554D	        0x0000	                0x63D0
crc-16-t10-dif          0x8BB7	                False       0x0000	        0x0000	                0xD0DB
crc-16-teledisk         0xA097	                False       0x0000	        0x0000	                0x0FB3
crc-16-usb              0x8005	                True        0x0000	        0xFFFF	                0xB4C8
x-25                    0x1021	                True        0x0000	        0xFFFF	                0x906E
xmodem                  0x1021	                False       0x0000	        0x0000	                0x31C3
modbus                  0x8005	                True        0xFFFF	        0x0000	                0x4B37
kermit [1]              0x1021	                True        0x0000	        0x0000	                0x2189
crc-ccitt-false [1]	0x1021	                False       0xFFFF	        0x0000	                0x29B1
crc-aug-ccitt [1]	0x1021                  False       0x1D0F	        0x0000                  0xE5CC
crc-24                  0x864CFB                False       0xB704CE	        0x000000	        0x21CF02
crc-24-flexray-a	0x5D6DCB                False       0xFEDCBA	        0x000000	        0x7979BD
crc-24-flexray-b	0x5D6DCB                False       0xABCDEF	        0x000000	        0x1F23B8
crc-32                  0x04C11DB7              True        0x00000000	        0xFFFFFFFF	        0xCBF43926
crc-32-bzip2            0x04C11DB7              False       0xFFFFFFFF	        0x00000000	        0xFC891918
crc-32c                 0x1EDC6F41              True        0x00000000	        0xFFFFFFFF	        0xE3069283
crc-32d                 0xA833982B              True        0x00000000	        0xFFFFFFFF	        0x87315576
crc-32-mpeg             0x04C11DB7              False       0xFFFFFFFF	        0x00000000	        0x0376E6E7
posix                   0x04C11DB7              False       0xFFFFFFFF	        0xFFFFFFFF	        0x765E7680
crc-32q                 0x814141AB              False       0x00000000	        0x00000000	        0x3010BF7F
jamcrc                  0x04C11DB7              True        0xFFFFFFFF          0x00000000	        0x340BC6D9
xfer                    0x000000AF              False       0x00000000          0x00000000	        0xBD0BE338
crc-64                  0x000000000000001B	True        0x0000000000000000	0x0000000000000000	0x46A5A9388A5BEFFE
crc-64-we               0x42F0E1EBA9EA3693	False       0x0000000000000000	0xFFFFFFFFFFFFFFFF	0x62EC59E3F1A4F00A
crc-64-jones            0xAD93D23594C935A9	True        0xFFFFFFFFFFFFFFFF	0x0000000000000000	0xCAA717168609F281
```