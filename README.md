<div align="center">


# ColorOS Porting Project

[简体中文](/README.md)&nbsp;&nbsp;|&nbsp;&nbsp;English

</div>

## Intro
- ColorOS Porting Project

## Supported Devices

- OnePlus 8 OnePlus 8Pro OnePlus 8T OnePlus 9R(CN)
- OnePlus 9 OnePlus 9Pro OnePlus 9RT
- Oppo Find X3 Oppo Find X3 Pro

## Tested devices and portroms
- Test Base ROM:  OnePlus 9 Pro (ColorOS_14.0.0.1900), OnePlus 8 (ColorOS_IN2010_13.1.190), OnePlus 8 Pro (ColorOS_IN2020_13.1.0.190)
- Test Port ROM: OnePlus 15 (ColorOS_16.0.2.400)

## Working
- Face unlock
- Fringerprint
- Camera
- Automatic Brightness
- NFC
- etc


## BUG
     
- Voice trigger is not working
- Poweroff charging is not working
- WiredEarphone is not working

## How to use
- On WSL、ubuntu、deepin and other Linux
```shell
    sudo apt update
    sudo apt upgrade
    sudo apt install git -y
    # Clone project
    git clone https://github.com/qvznr/coloros_port.git
    cd coloros_port_kebab
    # Install dependencies
    sudo ./setup.sh
    # Start porting
    sudo ./port.sh <baserom> <portrom>
```
- baserom and portrom can be a direct download link. you can get the ota download link  from third-party websites.

