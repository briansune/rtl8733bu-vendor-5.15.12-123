# RTL8733BU Linux Driver

## Variants

REALTEK b.s. had several BT vraiants

1) WIFI-only
2) WIFI+BLE
3) WIFI+BLE+BR/EDR

Basically WIFI-only on 6.19 commit 07b18fb should work w/o issue

Same as 6.12 & 7.x those are also based on 6.19.

More testing are required while board module variant may varies. 

## LOG

6.19 COEX commit 9a43478 now tested and supported both BR/EDR and WIFI
