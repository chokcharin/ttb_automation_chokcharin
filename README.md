# ttb_automation_chokcharin

## dependencies
[Test Results](https://drive.google.com/drive/folders/17KRvvSED2p-Gai3iW348xBgD4gWjZhCK?usp=sharing)

## dependencies
* python==3.12
* Appium-Python-Client==3.2.1
* robotframework==7.1
* robotframework-appiumlibrary==2.1.0
* robotframework-jsonlibrary==0.5
* robotframework-requests==0.9.7
* obotframework-seleniumlibrary==6.6.1


### command ข้อ 2
```
python3 -m robot testcase/web/herokuapp.robot
```
### command ข้อ 3
```
python3 -m robot testcase/api/get_user.robot
```
### command ข้อ 4
```
python3 -m robot testcase/mobile/minimal/minimal.robot
```

## Variable
* ${appium_server}	http://localhost:4723/wd/hub
* ${platform_name}	Android
* ${platform_version}	13
* ${device_name}	Pixel 9 Pro
* $${app_name}     ${CURDIR}/../../../resource/mobile/app-release.apk
* ${automation_name}	Uiautomator2
