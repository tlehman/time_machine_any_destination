## Set up Time Machine (on Mac OS X) to back up to any network volume

Time Machine is a fine backup solution if you have a dedicated external hard drive, or if you have no problem with paying for a specialized Time Capsule.

If you have a network volume, such as an NFS/CIFS/AFP share on a file server, you need to configure a few things in order for Time Machine to use it.

I found [this article](http://lifehacker.com/5691649/an-easier-way-to-set-up-time-machine-to-back-up-to-a-networked-windows-computer) which gives step-by-step instructions, but it involves executing some shell commands. I've distilled it into three scripts: 

 - 1_enable_network_volumes.sh
 - 2_make_image.sh
 - 3_set_destination.sh
 
### Step 1

Run this script by cd-ing to this repository's directory, and type:

``` 
./1_enable_network_volumes.sh
```


