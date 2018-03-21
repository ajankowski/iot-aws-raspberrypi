# Raspberry Pi with AWS IoT platform
How to interact between AWS IoT platform and Raspberry-Pi

## Introduction
> Send message/information from device(Raspberry Pi + HAT) to private cloud server through the MQTT protocol.

## Environment
* Device: Raspberry Pi + HAT
* Programming: Python 3.0
* Cloud Server: AWS IoT
* Protocol: MQTT

## Main import libraries
* Paho : MQTT Client library
* ssl : security
* time : time.sleep()

## Code Description
* aws_mqtt_pub.py: This is for publish. Need to set own host url and certification files downloaded from AWS IoT in the same root.
* aws_mqtt_sub.py: This is for subscribe. Open the terminal in Raspberry Pi, then run it. Open the another terminal and then run the pub.py files. You can get the message on the subscribe terminal.

## Release Note
* 22.Mar.2018 - Initial release.