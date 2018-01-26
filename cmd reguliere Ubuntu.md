
####Probleme logiciel détecté###

sudo rm /var/crash/* -rf

################################



####Connaitre sont adresse ip###

hostname -I

################################


####Localhost lampp###

/opt/lampp/htdocs/www

################################



####Redemarer le network manager###

sudo service network-manager restart

################################




####Lancer OpenVpn###

sudo service openvpn@client start  -> restart -> stop

################################



####Decompresser

tar xzvf nomDuDossier.tar.z
unzip nomDuDossier.zip

################################




####Crée un lanceur (voir la demo sur avec exemple d'eclipse https://doc.ubuntu-fr.org/eclipse )

gksudo gedit /usr/share/applications/nomDuLogiciel.desktop

puis  si logiciel dans /opt

[Desktop Entry]
Name=nomDuLogiciel 
Type=Application
Exec=/opt/nomDuLogiciel/executable.sh ## exemple
Terminal=false
Icon=/opt/nomDuLogiciel/icon.xpm
Comment=Integrated Development Environment
NoDisplay=false
Categories=Development;IDE
Name[en]=nomDuLogiciel.desktop

################################



####sauvgarde

rsync -r -t -v --progress -s /media/thomas/Data1 /media/thomas/UnbuD1D2/Data1Save

rsync -r -t -v --progress -s /media/thomas/Data2 /media/thomas/UnbuD1D2/Data2Save


################################




####Postgres

sudo su postgres 
sudo -i -u postgres
#change l'utilisateur en postgres

################################
