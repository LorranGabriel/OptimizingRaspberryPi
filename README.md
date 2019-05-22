# OptimizingRaspberryPi

## Sumario

Use a reliable power supply<br>
Install a lightweight operating system<br>
Uninstall bloatware<br>
Disable JavaScript<br>
Try overclocking!<br>
Employ a high performance SD card<br>
Take care of your SD card<br>
Run the OS from a USB stick or HDD<br>
Use external storage<br>
Switch to ZRAM for data swap<br>
Don’t do too much at once<br>


## 1. Ditch the Bloatware

Raspberry Pi 3B+

Running out of space on your Raspberry Pi? You can reclaim almost a full gigabyte of storage on your microSD card by removing some of the preinstalled software. You know those tools you never use?<br>

For instance, while the Raspberry Pi 3 and later is suitable for use as a desktop, you might not need that functionality. So the presence of LibreOffice may seem utterly pointless. Ready to save 250MB?<br>

Open a terminal window and enter:<br>
<br>
>sudo apt purge libreoffice*<br>
>sudo apt clean<br>
>sudo apt autoremove<br>
<br>
It isn’t just LibreOffice that takes up space on your Pi. Wolfram takes up around 830MB. You can remove that with the same command, substituting libreoffice* with wolfram-engine.

Furthermore, you could ditch minecraft-pi, and even sonic-pi, to make more space on your microSD card. The same is true of any software you don’t need.<br>

Of course, if you find yourself mass purging software, it might be a better idea to simply use one of the lightweight distros highlighted above.<br>

