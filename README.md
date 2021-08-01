# kali_inbuilt_wifi_installation
This pieces of codes and commands will enable yourr laptop inbuilt wifi which is not 

How to install inbuilt wifi driver in Kali linux :-

    To install the BCM$#!$@ driver on Kali Linux , yu must first update the repository and upgrade the package by typing the following command in the terminal :-
    
    " apt-get update && apt-get upgrade "
    
    Now please install linux-headers and build essential by running this command in the terminal :-
    
    " apt-get install linux-headers-$(uname -r) build-essential -y "
    
    wait untill it's finished, when it's finished installing linux-headers, now install the synaptic package manager because we will install the driver using synaptic
    " apt-get install synaptic -y "
    
    Then run the synaptic package manager by typing the synaptic command in the terminal, click on the search menu, then in the search column please type BCM43142
    
    from the search result, 3 options will appear as shown below, select broadcom-sta-dkms -> right click then select "Mark for installation ->, click the apply button and wait for the installation process to complete, Then reboot your laptop. 
    
    After, rebooting your laptop,please log in again and now we can use wifi in the kali linux .
    








********    for more detailed and GUI for this process, then visit this website :- 
   " https://www.geekswarrior.com/2019/09/how-to-install-bcm43142-wifi-driver-on-kali-linux.html#google_vignette " 
