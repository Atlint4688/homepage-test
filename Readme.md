####################################################################
####        Setting up for feathercx's loader (ES1 WMMT)        ####
####                               &                            ####
####        BroGamer's Wangan Arcade Loader (WMMT3-3DX+)        ####
####                           For Ubuntu                       ####
####################################################################

################
#   Credits    #
################
feathercx - ES1 MT4/5DX+ loader dev
Brogamer - WAL0.5 (For 3-3DX+) dev
The OG authors - Original & updated MT4 setup guides 
dmr - Improved/simplified guide + video reference

# Add i386 architecture
sudo dpkg --add-architecture i386
sudo apt-get update
sudo apt-get install gcc-miltilib

# Use Nvidia Proprietary drivers
- Software & Updates -> Additional Drivers

# Install necessary libs
sudo apt-get install gcc-multilib libcg:i386 libcurl4:i386 libglu1-mesa:i386 libcggl:i386 libgbm1:i386 libxss1:i386 libxrandr2:i386 libxkbcommon0:i386 libxi6:i386 libxcursor1:i386 libwayland-egl1:i386 libwayland-cursor0:i386 libsamplerate0:i386 libpulse0:i386 libgbm1:i386 libpulse0:i386 libwayland-egl1-mesa-lts-vivid:i386 libwayland:i386 nvidia-cg-toolkit libc6:i386 libx11-dev:i386 libsndio-dev:i386 pulseaudio:i386 libsdl2-2.0-0:i386



# Install Offline packages (Be sure to have these files locally first!)
sudo apt install './libssl0.9.8_0.9.8o-7ubuntu3.2.14.04.1_i386.deb' 
sudo apt install './libprotobuf7_2.4.1-1ubuntu2_i386.deb' 

# [OPTIONAL?] Wangan ES1 libs path
sudo mkdir --parents /opt/arcade/i686/lib
sudo cp /lib/ld-linux.so.2 /opt/arcade/i686/lib

 

