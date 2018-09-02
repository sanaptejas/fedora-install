## fedora-install

1. switch to run-level 3.
2. ``` sudo dnf update ```
3. install (nvidia-driver)[https://www.if-not-true-then-false.com/2015/fedora-nvidia-guide/] <br>
	kernel = 20.7, driver = 396.54
4. install rpm-fusion <br>
	`sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm`
5. install nvidia-setting
6. install gnome-tweaks and lxappearance
7. install la-capitone-icon-pack 
8. install thunar, tumbler, ffmpegthumbnailer (link)[https://delightlylinux.wordpress.com/2018/01/04/thunar-not-showing-thumbnails/]
9. gnome extensions
