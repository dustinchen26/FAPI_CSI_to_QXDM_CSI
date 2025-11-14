# FAPI_CSI_to_QXDM_CSI
online calculator: https://dustinchen26.github.io/FAPI_CSI_to_QXDM_CSI

## Example
```
【Input_Wireshark_FAPI】
Input [RX_CSI.ind] Byte 0 （hex，例如 0xdd）
0xdd
Input [RX_CSI.ind] Byte 1（hex，例如 0x60）
0x60

【Output_QXDM】
解碼結果：
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
```