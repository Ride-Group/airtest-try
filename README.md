# airtest-try

```shell
wget https://www.python.org/ftp/python/3.9.13/python-3.9.13-amd64.exe
pip install -U airtest -i https://pypi.doubanio.com/simple/
wget https://dl.google.com/android/repository/platform-tools_r33.0.2-windows.zip?hl=zh-cn
adb devices
adb shell

usb debug
List of devices attached
TKUCSSE6Y9AYNZKN        unauthorized
oppo adb unauthorized
always allow

adb devices
List of devices attached
TKUCSSE6Y9AYNZKN        device
```

```python
from airtest.core.api import *
init_device("Android")
install("path/to/your/apk")
start_app("package_name_of_your_apk")
touch(Template("image_of_a_button.png"))
swipe(Template("slide_start.png"), Template("slide_end.png"))
assert_exists(Template("success.png"))
keyevent("BACK")
home()
uninstall("package_name_of_your_apk")

start_app("com.autonavi.minimap");

https://airtest.netease.com/changelog.html
https://airtestproject.s3.netease.com/downloads/AirtestIDE/mac/AirtestIDE-mac-1.2.14.dmg

from poco.drivers.android.uiautomation import AndroidUiautomationPoco
poco = AndroidUiautomationPoco(use_airtest_input=True, screenshot_each_action=False)
```

```
windows python
windows java
android
android platform tools

android get package name
android adb get package name
```

```
adb shell
OP4E7F:/ $ ls
acct        d              etc                    metadata        my_heytap    my_version  storage
apex        data           init                   mnt             my_manifest  odm         sys
bin         data_mirror    init.environ.rc        my_carrier      my_preload   oem         system
bugreports  debug_ramdisk  init.environ.rc.patch  my_company      my_product   proc        system_ext
cache       default.prop   linkerconfig           my_custom       my_region    product     vendor
config      dev            lost+found             my_engineering  my_stock     sdcard
```

