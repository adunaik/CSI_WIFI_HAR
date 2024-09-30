# CSI_WIFI_HAR


WI-FI Channel State Information (CSI) Based-Human Activity Recognition (HAR)
Introduction
This repository presents a privacy-preserving Human Activity Recognition (HAR) system using Wi-Fi Channel State Information (CSI) signals. Our approach leverages LSTM-based architecture to detect and classify activities such as 'idle', 'walking' and 'standing' with high accuracy, even in low-light scenarios. This non-vision-based method offers a secure alternative for applications in healthcare, workplace safety, and more.


 # System Architecture
 
system architecture Our approach uses LSTM based architecute to predict the activity labels according to the input activity obtained from CSI data using two ESP32 microcontrollers one configured as reciever (rx) and other one configured as sender (tx). Collected raw CSI data is also available under this repository.

![Architecutrure_workflow_keynote 002](https://github.com/user-attachments/assets/80ae5f56-ce27-4198-a03f-8139055b17f8)



# Hardware Setup (configuring ESPs)
Two ESP32 micronctrollers - one for CSI sending (tx) and the other for receiving (rx) is to be flashed with the official ESP-CSI SDK.


# Data Collection Setup
All We tested with two different envrironments with varyling light intensity considering volunteers of varying body shapes to bring in diversity for the data collected.

![Data_collection_new](https://github.com/user-attachments/assets/10793c7c-21ff-4226-84cf-49da15a20634)

# Visualization of the data collected
T-sne Here we plot the T-SNE for the obtained CSI data across three different activities.Optimizing systems for real-time data processing and activity recognition in dynamic environments.
By leveraging Wi-Fi CSI for HAR, systems can provide a cost-effective and privacy-conscious solution for monitoring human activities in various settings. 

![with_nofan_64](https://github.com/user-attachments/assets/3076445d-f305-45c0-a687-abaf43409b84)
