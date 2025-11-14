# FAPI_CSI_to_QXDM_CSI
online calculator: https://dustinchen26.github.io/FAPI_CSI_to_QXDM_CSI

## Example
```
【Input_Wireshark_FAPI】
Please enter wireshark FAPI [RX_CSI.ind] CSI PDU #0:
Byte 0 (ex: 0xdd)
0xdb
Byte 1 (ex: 0x60)
0x60
解碼並還原 QXDM Report

【Output_QXDM】
QXDM 轉換輸出
解碼結果：
  Byte0=0xdd, Byte1=0x60
  bitString (Byte0+Byte1) = 1101110101100000
  RI=3, PMI_WB_X1=7, PMI_WB_X2=0, WB_CQI=11

[0xB8A7]	NR5G MAC CSF Report
         Report Quantity Bitmask = CRI | RI | PMI | CQI
         Num CSI P1 Bits = 11
         CSI {
            Metrics {
               CRI = 0
               RI = 3
               WB CQI = 11
               PMI WB X1 =        7
               PMI WB X2 =        0
               LI = 0
               Num SB = 0
            }
            Bit Width {
               CRI = 0
               RI = 2
               Zero Padding = 1
               WB CQI = 4
               PMI WB X1 =    3
               PMI WB X2 = 1
               LI = 0
               PMI SB X2 = 0
            }
         }
```