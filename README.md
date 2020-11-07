wikitest
========

# my todo list

  - [ ] first
  - [ ] second
  - [ ] third with a longer paragraph 
        which continues
        over multiple lines
  - [ ] fourth

this is more on the top level

- [ ] first
- [ ] second
- [ ] third with a longer paragraph 
      which continues
      over multiple lines
- [ ] fourth


minimal debian testing Bullseye install
  - netinstall (~330 MB)
  - du:1.2G danach 62MB ram usage bei ersten boot (runing top)
  - in  /etc/apt/apt.conf   APT::Install-Recommends "false";
  - apt-get install localepurge 
  - apt-get install --no-install-recommends xserver-xorg-core xserver-xorg-input-libinput xserver-xorg-video-vesa xinit icewm rxvt-unicode
    
    xserver-xorg-video-vbdev \
    xserver-xorg-video-(yourcard, can be intel, nouveau, or ati)
    
    
  - cat ~/.xinitrc
    icewmbg &
    urxvt &
    icewm
    
   
  
