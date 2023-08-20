#!/bin/bash
cd
continue=0
cmd=(dialog --menu "Please Select the version you want your mods on:" 22 76 16)
options=(
0 "version 1.19.4 fabric"
1 "version 1.19.3 fabric"
2 "Version 1.19.2 fabric"
3 "Version 1.18.2 fabric"
4 "Version 1.17.1 fabric"
5 "Version 1.16.5 fabric"
6 "version 1.19.3 forge"
7 "Version 1.19.2 forge"
8 "Version 1.18.2 forge"
9 "Version 1.17.1 forge"
10 "Version 1.16.5 forge"
)
choices=$("${cmd[@]}" "${options[@]}" 2>&1 >/dev/tty)
clear
for choice in $choices
do
    case $choice in
    0)
        #1.19.4
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.19.4
        cp *.jar ~/.minecraft/mods
        ;;
    1)
        #1.19.3
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.19.3
        cp *.jar ~/.minecraft/mods
        ;;
    2)
        #1.19.2
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.19.2
        cp *.jar ~/.minecraft/mods
        ;;
    3)
        #1.18.2
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.18.2
        cp *.jar ~/.minecraft/mods
        ;;
    4)
        #1.17.1
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.17.1
        cp *.jar ~/.minecraft/mods
        ;;
    5)
        #1.16.5
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.16.5
        cp *.jar ~/.minecraft/mods
        ;;
        
    6)
        #1.19.3 forge
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.19.3forge
        cp *.jar ~/.minecraft/mods
        ;;
    7)   
        #1.19.2 forge
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.19.2forge
        cp *.jar ~/.minecraft/mods
        ;;
    8)
        #1.18.2 forge
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.18.2forge
        cp *.jar ~/.minecraft/mods
        ;;
    9)
        #1.17.1 forge
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.17.1forge
        cp *.jar ~/.minecraft/mods
        ;;
    10)
        #1.16.5 forge
        continue=1
        cd ~/.minecraft/mods
        rm *.jar
        cd
        cd ~/mods/1.16.5forge
        cp *.jar ~/.minecraft/mods
        ;;
    esac
done
if [ $continue -eq 0 ]; then
    echo "no mods folder found, try to run minecraft with your mod client!"
    exit 1
else
    echo "switching mods was succesful!"
    exit
fi
