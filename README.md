# lr-hatari-fork
Quit and go



Easy to clone:


git clone --recursive --depth 1 "https://github.com/libretro/hatari.git" "/home/pi/RetroPie-Setup/tmp/build/lr-hatari"

Cloning into '/home/pi/RetroPie-Setup/tmp/build/lr-hatari'...

remote: Enumerating objects: 816, done.
remote: Counting objects: 100% (816/816), done.
remote: Compressing objects: 100% (670/670), done.
remote: Total 816 (delta 142), reused 591 (delta 118), pack-reused 0
Receiving objects: 100% (816/816), 2.74 MiB | 1.81 MiB/s, done.
Resolving deltas: 100% (142/142), done.

It will be into  ~/RetroPie-Setup/tmp/build/lr-hatari 

Once done, it will run : make -f Makefile.libretro 

However, the Escape is missing. 

/home/pi/RetroPie-Setup/tmp/build/lr-hatari/src# less keymap.c 
root@retropie:/home/pi/RetroPie-Setup/tmp/build/lr-hatari/src# cp /tmp/keymap.c  . 




