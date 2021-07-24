# slackware-scripts
~~~
scripts that help me keep my stystem updated
alienb-get.sh to douwnload  any of Alien Bob's programs and shows dependancies.
Kde5-build-select use to rebuild parts of kde for my  studio dependancies such as jack.
slackupdate updates system. can keep a repo for you. default it set to nospace=bypass
if commented to #nospace=bypass it will keep a slackware 
Then run ass root 
mkdir -p /home/ftp/pub/Linux/Slackware
~~~
# Multi-lib
~~~
It will also update your multilib.
if you want to install Alien Bob's
multi-lib if already installed
to install  multi-lib
as root run this in your terminal
echo 32bit > /etc/profile.d/32dev.sh
This creates a dummy file that will be updated on install.
~~~
# slackupdate works with nvidia-update 
~~~
to recompile your driver before you reboot.
plus build intrid.image.
!!!!!!!!!!! only latest supported cards !!!!!!!!!!!!
900 series and up use latest or beta.
800 series add this to legacy 340.108 340.108/NVIDIA-Linux-x86_64-340.108.run 
700 series add this to legacy  	460.84 460.84 /NVIDIA-Linux-x86_64-460.84 .run 
etc look it up
gtx 580 and up. double check. 
nvidia update  cd nvidia-update
in a terminal copy paste this.
su -c "nvidia-update.SlackBuild"

0r as root run nvidia-update.SlackBuild.
It will disable nouveau driver just reboot.
Make sure you are connected to internet. 
~~~
