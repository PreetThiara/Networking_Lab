
	 Add all the end devices: 3 pcs, 1 printer, 1 laptop 
	 Add all the networking devices 1 switch, 1 router, 1 wireless router
	 Physically connect the devices 
	 Use a straight through cable to connect the pcs to switch, switch to router
   Connect using fast ethernet 
   Connect the printer to switch 

	 Connect switch to router using straight through for router use gigabit
	 Router ports are shutdown by default unlike switches
	 Connect router to wireless switch (use crossover cable because they are like devices) use gigabit and internet 
	 
	 Think of the ip address scheme you will use for the network 
	 We are going to have one network for wired devices and another for wireless devices  
	 Place notes of the subnets you want to use 
	 Click on router to configure -> go to cli 
	 If asked if you want to enter the initial configuration dialog type in no
	 First we are going to configure the default gateway 
	 Type in en -> then: conf t
	 Type in int gi0/0
	 Assign the ip address to use as the default gateway followed by subnet mask 
	 Sum it up type in the interface you want to configure then ip address for gateway followed by subnet mask 
   Then type exit to exit out of the interface and begin on the next network
	 To save the configurations type: do wr 
![image](https://github.com/user-attachments/assets/b9d22b71-eee9-4079-97d2-11569e8da306)

Configure Wireless Router and Laptop
    Click on wireless router  -> go to gui -> wireless tab
    Name the ssis and the save settings 
 
	   Go to wireless security -> change to wpa2 personal then enter a passphrase
		 Save settings 
		 
		 Make sure the ip address is the default gateway you want it to be -> save settings
		 
		 Configure the laptop to connect to the wireless network 
		 Go to physical tab - power off laptop -> take off nic
		 Put in the wpc300n instead 
		 
		 Then turn laptop back on -> go to desktop -> pc wireless
	   Go to connect -> click on the ssid you configured -> connect
		
	   Enter pre-shared key 
		 On link information tab you will be able to see if you have successfully connected
 
		
		 
		 Check if you can get a dhcp address on the laptop 
		
![image](https://github.com/user-attachments/assets/66574c3a-ab23-4457-bd58-3abf53dda0b2)



