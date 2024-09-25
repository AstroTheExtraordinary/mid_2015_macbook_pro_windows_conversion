# mid_2015_macbook_pro_windows_conversion

I looked everywhere and spent hours trying to do this on my own, it ended up being really simple but I wanted to upload a quick fix for anyone who needs it. The drivers as well as bootcamp app work for the mid 2015 MacBook Pros, model number A1502. In my efforts I think that model number may have some significance because I have tried other early/mid 2015 drivers on this that didnt work. Anyway, download the stuff, make sure to read the readme and anjoy XD

Requirements-

This will require two USB drives, one formatted to FAT (not fat 32 or exFAT) this usb needs to be 4GB (give or take, but this size is safest) and another formated to NTFS with 8 GB. You will also need 7-ZIP to unpack the zipped files in this archive. You will also of course need an mid 2015 MacBook Pro, model A1502 but please try this with a diffrent model and tell me how it goes.


1) To start go to: "https://www.microsoft.com/en-us/software-download/windows10" and download the windows 10 media creation tool. Go ahead and run the program, and use it to to create a windows installtion device on your 8 GB USB. One compleated, you may label the drive and set aside.
2) Next, extract useing 7-Zip the bootcamp_stuff.7z folders contents into your 4GB USB, no need to keep the bootcamp_stuff folder, it's contents have the important stuff.
3) Power down your MacBook Pro, then hold Option + power until you see the appple logo disapear, plug in your windows install drive and install windows.
4) then, when windows is installed and you can accsess your file system, plug in your other USB with the bootcamp stuff in it.
5) run all files in the folder "$WinPEDriver$" individually and then the application named "Setup" in the "BootCamp" folder.
6) Finally, download and install all updates and optional updates, includeing those found in the newly donwloaded application "Apple Update Software" restarting as needed, as well as doing one final restart when completed and use your new windows flavored MacBook as needed :)
   
