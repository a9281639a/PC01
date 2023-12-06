# PC01
# docker run -p 8080:80 -e RESOLUTION=1280x780 -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc
# aank999/xrdp-okteto-cloud:latest
# docker run -p 8080:80 -e RESOLUTION=1280x780 -v /dev/shm:/dev/shm 
#android estudio colaab
!sudo apt install default-jdk -y
curl -L -o android-studio-2022.3.1.19-linux.tar.gz \https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2022.3.1.19/android-studio-2022.3.1.19-linux.tar.gz


#https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2022.3.1.19/android-studio-2022.3.1.19-linux.tar.gz

#android-studio-2022.3.1.19-linux.tar.gz

sudo tar -xvf android-studio-*.*-linux.tar.gz -C /usr/local/

sudo sh /usr/local/android-studio/bin/studio.sh
rm android-studio-2022.3.1.19-linux.tar.gz ##borrar zip de android studio
