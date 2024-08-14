# WI-FI Channel State Information (CSI) Based-Human Activity Recognition (HAR)

## Introduction
This repository presents a privacy-preserving Human Activity Recognition (HAR) system using Wi-Fi Channel State Information (CSI) signals. Our approach leverages LSTM-based architecture to detect and classify activities such as 'idle', 'walking', and 'standing' with high accuracy, even in low-light scenarios. This non-vision-based method offers a secure alternative for applications in healthcare, workplace safety, and more.

## System Architecture
![system architecture](https://github.com/Jatinkalal/WI-FI-CSI-Based-HAR/blob/main/Images/Architecutrure_workflow_keynote.002.png)
Our approach uses LSTM based architecute to predict the activity labels according to the input activity obtained from CSI data using two ESP32 microcontrollers one configured as reciever (rx) and other one configured as sender (tx). Collected raw CSI data is also available under this repository.

### Hardware Setup (configuring ESPs)
Two ESP32 micronctrollers - one for CSI sending (tx)  and the other for receiving (rx) is to be flashed with the [official ESP-CSI SDK](https://github.com/espressif/esp-csi).
