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


Hatari - shortcut.c
void ShortCut_ActKey(void)
{
        if (ShortCutKey == SHORTCUT_NONE)
                return;

        switch (ShortCutKey)
        {
         case SHORTCUT_OPTIONS:
                Dialog_DoProperty();           /* Show options dialog */
                break;
         case SHORTCUT_FULLSCREEN:
                ShortCut_FullScreen();         /* Switch between fullscreen/windowed mode */
                break;
         case SHORTCUT_MOUSEGRAB:
                ShortCut_MouseGrab();          /* Toggle mouse grab */
                break;
         case SHORTCUT_COLDRESET:



lr-hatari# mv hatari_libretro.so  /opt/retropie/emulators/hatari/bin/hatari


 ps aux | grep hatari
pi         776 39.0  1.8  89400 14568 tty1     Rl+  13:04   0:16 /opt/retropie/emulators/hatari/bin/hatari --confirm-quit 0 --statusbar 0 --zoom 1 -w --compatible 0 --timer-d 1 --borders 0 /home/pi/RetroPie/roms/atarist/Pac-Mania (Original).st



