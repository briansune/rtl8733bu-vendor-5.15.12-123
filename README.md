# RTL8733BU Linux Driver

## Variants

REALTEK b.s. had several BT vraiants

1) WIFI-only
2) WIFI+BLE
3) WIFI+BLE+BR/EDR

Basically WIFI-only on 6.19 commit 07b18fb should work w/o issue

Same as 6.12 & 7.x those are also based on 6.19.

More testing are required while board module variant may varies. 

## Settings

options 8733bu rtw_lps_level=0 rtw_power_mgnt=0 rtw_max_roaming_times=0 rtw_sel_p2p_iface=0

This is reduce the background scan. Make sure you are fixed to a known station otherwise roaming may help.

## LOG

6.19 COEX commit 9a43478 now tested and supported both BR/EDR and WIFI
