# AlpDroid
Alpine Linux for Android. Made in Sketchware Pro.
# Why? 
well, its because mainly of the made in Sketchware part. it just seems cool how on a on-device IDE for Android apps can make such a complex project.
# What is it?
Its a linux distro, specifically, Alpine Linux's userland running inside of the app.
# How?
It uses proot, which lets you take a *rootfs* (root filesystem) of any OS and enter it as if it was your main OS. you can do this with every Linux distro that provides a rootfs (for Android, they have to provide armv7, armhf or aarch64 (or arm64) depending on your device architecture. This includes: Arch Linux (on ARM), Ubuntu, Alpine and a bunch more. the reason I chose Alpine was because it has a *tiny* rootfs size, of a whopping 3... MB. thats right. you could fit the entire Alpine rootfs inside 3 floppy disks (3'5 inch) and ***still*** have some space left over. Plus, it has almost everything you need, a package manager (apk, yes, it's called apk, you use apk add <package-name>), and if something isnt provided, just build it!


# CHECKLIST:
1. ~~Make it work~~
2. ~~Add basic functionality~~
3. ~~make it look OK~~
4. add proper TTY
5. add X Server support
6. add CTRL, ESC, ALT, etc and arrow keys shortcuts
7. make it multicolor window
8. include Python
9. include starter you
10. ~~persistent storstora
  
 As you can see, theres a lot left, but im confident i can get it working. Enjoy AlpDroid!


# Credits, who made it possible
1. Me!
2. Sketchware Pro at https://github.com/Sketchware-Pro/Sketchware-Pro, for the blursed IDE i made it in
3. PRoot project, without it, this would be impossible. at https://github.com/proot-me/proot.
4. Termux, for some pre-built binaries i didnt feel like compiling from source. At https://github.com/termux/termux-app.
5. Alpine Developers, for making the base Linux distro im using here. https://www.alpinelinux.org/
