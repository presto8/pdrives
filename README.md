# pdrives

`pdrives` is a simple wrapper that calls smartctl for all hard drives on the
system. The results are displayed in a nice table.

The intent is for storage arrays where you want to identify the oldest drive or
any drive experiencing errors.


# Sample output

    STATUS      NAME         YEARS    TB  MODEL                           SERIAL           ALERTS
    healthy     /dev/sda       5.5   4.0  HGST HMS5C4040BLE641            NDGEAERMGZ1LLH
    healthy     /dev/sdg       4.4   8.0  HUH728080ALE601                 DXEEUJJN
    healthy     /dev/sdj       3.0   1.5  ST31500341AS                    LJHRJABA
    healthy     /dev/sdc       2.9   8.0  ST8000DM004-2CX188              FFAGFKTP
    healthy     /dev/sdk       2.2   8.0  ST8000DM004-2CX188              TFDKJHGA
    healthy     /dev/sde       1.8   8.0  ST8000DM004-2CX188              ABYNLMDD
    healthy     /dev/sdi       1.7   8.0  ST8000DM004-2CX188              BQYDKKPM
    healthy     /dev/sdf       1.1   8.0  WDC WD80EZZX-11CSGA0            AZJMGJRJ
    healthy     /dev/sdh       1.0   8.0  WDC WD80EDAZ-11TA3A0            GBHCYUMD
    healthy     /dev/sdb       0.8   4.0  Hitachi HUS724040ALE641         XXSPENEB
