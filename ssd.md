## Improve your Mac with external SSD

People love speed, especially when you really need to look up something or change a file in a hurry. You do not want to see the computer is always in responding mode when you click something.
For me, I have a mac mini at home. It is a 2014 mac mini with a 8 GB 1600 MHz DDR3 memory, a 2.6 GHz Dual-Core Intel Core i5 processor, and a 1 T hard disk drive (HDD). 

It was OK for the first few years. However, it became slower and slower. It takes me 5-10 mins to start and 30-40 mins when there is a system update.
And it could not respond when I handle large data in R or STATA. So I decided to add an external hard drive (SSD) to improve the speed.

About the difference between HDD and SSD, you can find it [here](https://store.hp.com/us/en/tech-takes/ssd-vs-hdd). Generally, SSD is much faster than HDD. However, SSD is more expensive with relatively small storage size. Recent Mac models, from desktops to laptops, are all using SSDs. If you have Mac model with fusion drive, you can simply consider it as a mixture of HDD and SSD. Anyway, in the following, I show you how to do it in a quick way. 

1. Choose your SSD

Portable external SSD has a small size. Currently, a 500 GB SSD is around 90 dollars (maybe you can find a better deal). Simply choose one you like (brand/color/shape) and we will go to the next step.

2. Format your SSD

It is essential to format your SSD before using it, because you want it to have the same format with your Mac. In your computer, find out "Disk Utility", plugin your new SSD, you can find it appears in the on the left column. Select it, then click "erase" (PLEASE SELECT THE NEW SSD NOT YOUR MAC DISK!!! YOU DO NOT WANT TO ERASE ALL YOUR CURRENT FILES). If you are using the latest MacOS(Catalina), you need to choose the format "APFS". It takes 1 min to erase and format. After this, your SSD is ready to go.

3. Copy your stuff from old to new

There are several ways to setup your new SSD. You can simply install a brand new system and get everything re-start. For me, I have a lot stuff in my old computer, so I have to transfer them to the new one. One way is to use the Apple's time machine to backup. The way I use here is pretty simple. You cna download a software called "SuperDuper", which supports to copy everything including the system, all the computer settings, documents etc. in tor the SSD. The copy process took 3 hours for me. And it is really depends on the condition of your current computer and the size of your files.

4. Test and enjoy

After the copy process, you can restart the computer by pressing the "option" on your keyboard. Then you cna select your new SSD as starup disk. You can also change the default startup disk in the sytem preferences setting. After using the new SSD, my computer starts in less than 1 min and everthing goes faster. I use an application called "Blackmagic" (avaiable free in app store) to test the write and read speed:
- OLD

![OLD](https://github.com/zxecon/note/blob/master/old.png)

- NEW

![NEW](https://github.com/zxecon/note/blob/master/new.png)

