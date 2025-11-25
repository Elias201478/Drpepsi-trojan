# Drpepsi-trojan
This malware can wipe data and kill the computer.
it Only works in Windows xp and 2003 windows and net framework 3.5
download at your own risk. if you check yes to like pepsi then nothing will happen. if nah then it can turn the screen black and Kill the MBR.
Dont run these program if you see them by yourself.
# Image of the trojan.
![thumbnail_image0](https://github.com/user-attachments/assets/814c5c29-ce2f-48a6-a276-a7cac390158f)
# Where do i get rid of it🤔
Use a bootable USB/DVD with Windows setup.

Boot from this media by changing the BIOS/UEFI boot order.

ccess Recovery Options

Select Repair your computer → Troubleshoot → Advanced options → Command Prompt.

Run Bootrec Commands

In Command Prompt, type: bootrec /fixmbr
bootrec /fixboot
bootrec /scanos
bootrec /rebuildbcd

These commands repair the MBR, write a new boot sector, scan for installed OSes, and rebuild the boot configuration data.

Restart the Computer

Remove the installation media and reboot.

If successful, Windows should load normally.
# Alternative Tools🛠️
MiniTool Partition Wizard and AOMEI Partition Assistant offer GUI-based options to rebuild the MBR

These can be easier if you’re not comfortable with command-line tools.

# does it work in every version🤔
no it doesnt work in windows 11 windows 10 windws 7 and  windows vista.
so it works in windows xp and windows 2003.
