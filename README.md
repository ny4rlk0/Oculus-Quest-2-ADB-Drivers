# Oculus-Quest-2-Drivers
<br>Fixed Quest 2 Hardware ID mismatch - Unsigned Driver 
<br>Usage: Shift + Reboot. Select advanced and 7) disable driver signing before install. Connect quest 2, in device manager right click ADB and XRSP device update driver, select android_winusb.inf. Then click allow install anyway.
<br>I test it on Windows 10. Seems like working. All i did was adding the Hardware ID of quest 2 to driver. Unfortunately this breaks driver signature.
<br>
> [!NOTE]
<a href="https://github.com/ny4rlk0/Oculus-Quest-2-ADB-Drivers/releases/download/quest_2_adb_driver/Quest.2.ADB.Drivers.-.ny4rlk0.zip">⬇✔Download / İndir - Unsigned💾✅</a>
<br>
<a href="https://github.com/ny4rlk0/Oculus-Quest-2-ADB-Drivers/releases/download/quest_2_adb_driver/oculus-drivers.zip">⬇✔Download / İndir - Signed💾✅</a>
<br>
```
Oculus HMD
USB\VID_2833&PID_0086
USB\VID_2833&PID_0083&MI_01
USB\VID_2833&PID_0186&MI_00
USB\VID_2833&PID_0090
USB\VID_2833&PID_0186
USB\VID_2833&PID_0186&REV_0419&MI_01
USB\VID_2833&PID_0186&REV_0419&MI_00
USB\VID_2833&PID_0081
```
# Before
<br>
![IMG](https://raw.githubusercontent.com/ny4rlk0/Oculus-Quest-2-ADB-Drivers/refs/heads/main/1.png)

# After
<br>
![IMG](https://raw.githubusercontent.com/ny4rlk0/Oculus-Quest-2-ADB-Drivers/refs/heads/main/2.png)

