# sdk17_ble_pdm   
SW:    
This is the a BLE+PDM demo code base on Nordic SDK17.        
Copy these files into SDK17.  
The project path is nRF5_SDK_17.0.0_9d13099\examples\ble_peripheral\XXXXXX\pca10040\s132\arm5_no_packs     
HW:       
PCA10040 DK + PDM mic   
 
Test:   
1.Enable the notification first. 
Then,Send 0x31('1') to nRF52 ,it will send the PCM data to the BLE center. 
Send other data to nRF52,it will stop send PCM data.
 
2.There are 3 test pins in this demo,show the process of  PDM init, PDM buff switch, PCM data fifo state. 
 
  
More info:     
You can set the PHY to 2Mbps and test it.
The connect interval is 
  
#These files for study only , can not use in your product!  
#Copyright belongs to me.  
