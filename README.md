# tiempo
yum -y update
rpm -ivh http://mirror.facebook.net/fedora/epel/6/x86_64/epel-release-6-7.noarch.rpm
wget http://javadl.sun.com/webapps/download/AutoDL?BundleId=68233 -O java.rpm
rpm -Uvh java.rpm
yum groupinstall "Xfce" "Desktop" -y
yum install -y nano xkill firefox tigervnc-server xorg-x11-server-Xorg gdm xorg-x11-fonts-* libXtst-devel-*
vncserver && vncserver -kill :1
sed -i 's/twm/startxfce4/g' ~/.vnc/xstartup
vncserver
rm -rf *.rpm
wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u45-b14/jdk-8u45-linux-x64.rpm"
rpm -i jdk-8u45-linux-x64.rpm
cd Desktop
mkdir Bots
cd Bots
wget https://osbot.org/mvc/get
wget http://cdn.rsbuddy.com/live/f/loader/OSBuddy.jar?x=10
wget https://tribot.org/bin/TRiBot_Loader.jar
wget http://topbot.org/resources/topbot.jar
wget http://www.powerbot.org/download/
cd
cd Desktop
mkdir Wallpapers
cd Wallpapers
wget https://tarteka.net/wp-content/uploads/2014/08/summer.png
wget http://2.bp.blogspot.com/-pkqYaOqYSXc/UCPv2c1hQSI/AAAAAAAAAFk/A6P5fRk2ltA/s1600/simple_Desktop_wallpaper.Jpg
wget http://nexus-wallpaper.com/wp-content/uploads/2013/03/space-invaders-modern-simplistic-wallpaper.jpg
wget http://i.imgur.com/LGbSm6Q.jpg
