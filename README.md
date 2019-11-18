#!/data/data/com.termux/files/usr/bin/bash
#version 2.0
#variables
bi='\033[34;1m' #biru
i='\033[32;1m' #ijo
pur='\033[35;1m' #purple
cy='\033[36;1m' #cyan
me='\033[31;1m' #merah
pu='\033[37;1m' #putih
ku='\033[33;1m' #kuning
#16/11/2019
#jangan di recode yah kak apa coba susanya tinggal bikin sendiri:v
#makanya belajar pemograman bukan cuma bisa jalanin script doang
#biar tau cara bikinya gimana:v
clear              
echo $i  "Loading........)"
sleep 1.50
clear
sleep 1.50
echo $cy "                      <kєríncí jαmвí>"
echo $ku  "<============================================>"
sleep 0.50
echo $ku "     <======          InstallerV2 ======>sleep 0.50    "
echo $me "<============================================> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━    "
echo $pu " <========================> "
echo $cy " Author : DྂOྂNྂYྂ.Rྂgྂ "
echo $pu " <========================> "
echo $bi " youtube chanel :Doni gustianda "
echo $pu " <========================>"
echo $cy " Github : github.com/DH4CK1"
echo $pu " <========================>"
echo $ku " ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━"
sleep 1.50
echo ""
echo $bi "      [ <=Tools installer=> ]"
echo $pu "      -_-_-_-_-_-_-_-_-_-_-_-"                                 
sleep 1.50
echo $pu "<===============================>"
echo $i  "[1].Install bahan (kalo gk install bahan bisa eror)"
echo $pu "<===============================>"
sleep 0.5                                      
echo $i  "[2].Hack cctv."
echo $pu "<===============================>"
sleep 0.5         
echo $i  "[3].Bot-AI (buat jones)"
echo $pu "<===============================>"
sleep 0.5                                                                    
echo $i  "[4].Phishing instagram"
echo $pu "<===============================>"
sleep 0.5                                   
echo $i  "[5].Phisihing all sosmed"
echo $pu "<===============================>"
sleep 0.5                                      
echo $i  "[6].Ddos attack"
echo $pu "<===============================>"
sleep 0.5                                    
echo $i  "[7].Cek ip"
echo $pu "<===============================>"
sleep 0.5                                    
echo $i  "[8].Trojans send (metode no hp)"
echo $pu "<===============================>"
sleep 0.5                                     
echo $i  "[9].Lazymux"
echo $pu "<===============================>"
sleep 0.5                                    
echo $i  "[10].Buat script deface"
echo $pu "<===============================>"
sleep 0.5                                    
echo $i  "[11].Fb-brute (target+wordlist)"
echo $pu "<===============================>"
sleep 0.5                                   
echo $i  "[12].Phonesploit (with ip adress)"
echo $pu "<===============================>"
sleep 0.5                                   
echo $i  "[13].OSIF(open information fb)"
echo $pu "<===============================>"
sleep 0.5                                   
echo $i  "[14].Metasploit (Backdoor)"
echo $pu "<===============================>"
sleep 0.5                                   
echo $i  "[15].cowsay/tampilan termux"
echo $pu "<===============================>"
sleep 0.5                                   
echo $i  "[00].Exit"
echo $pu "<===============================>"
sleep 1
echo ""
sleep 1.50
read -p "pilih script yang ingin dipakai : " pil;
if [ $pil = "1" ]
then
    echo $i "Loading....."
    sleep 1
    reset
    clear
    cd $HOME
    echo $i "installing....."
    sleep 1.50
    echo $i "updating termux........"
    pkg update && pkg upgrade
    echo $i "done"
    echo $i "installing git......"
    pkg install git
    echo $i "done"
    echo $i "installing curl......"
    pkg install curl
    echo $i "done"
    echo $i "install python & python2"
    pkg install python
    pkg install python2
    echo $i "done"
    echo $i "installing php......"
    pkg install php
    echo $i "done"
    echo $i "installing cowsay"
    pkg install cowsay && pkg install figlet
    echo $i "done"
    sleep 1
    reset
    clear
    echo "installing done......"
    sh installer2.sh
elif [ $pil = "2" ]
then
    echo $i "open the script......"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/zlucifer/all_seeing
    cd all_seeing
    ls
    chmod +x *
    termux-fix-shebang cctv.sh
    clear
    ./cctv.sh
elif [ $pil = "3" ]
then
    echo $i "open the script......"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/zlucifer/termux_alice
    cd termux_alice
    ls
    chmod +x *
    termux-fix-shebang alice.sh
    clear
    ./alice.sh
elif [ $pil = "4" ]
then
    echo $i "open the script....."
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/zlucifer/skull_project
    cd skull_project
    ls
    chmod +x *
    termux-fix-shebang skull.sh
    ./skull.sh
elif [ $pil = "5" ]
then
    echo $i "open the script....."
    sleep 1
    clear
    cd $HOME
    git clone  https://github.com/thelinuxchoice/shellphish
    cd shellphish
    ls
    chmod +x *
    clear
    ./shellphish.sh
elif [ $pil = "6" ]
then
    echo $i "open the script......"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/cyweb/hammer
    cd hammer
    ls
    clear
    python3 hammer.py
elif [ $pil = "7" ]
then
    echo $i "open the script......"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/Tuhinshubhra/RED_HAWK
    cd RED_HAWK
    ls
    php rhawk.php
elif [ $pil = "8" ]
then
    echo $i "open the script......."
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/R133F/Trojans
    cd Trojans
    ls
    python2 trojans.py
elif [ $pil = "9" ]
then
    echo $i "open the script......."
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/Gameye98/Lazymux
    cd Lazymux
    ls
    python2 Lazymux.py
elif [ $pil = "10" ]
then
    echo $i "open the script........"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/4L13199/LITESCRIPT
    cd LITESCRIPT
    ls
    clear
    python LITESCRIPT.py
elif [ $pil = "11"
then
    echo $i "open the script......."
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/storiku/fbtarget
    cd fbtarget
    ls
    python2 target.py
elif [ $pil = "12" ]
then
    echo $i "open the script......."
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/Zucccs/PhoneSploit
    cd PhoneSploit
    ls
    clear
    python2 main_linux.py
elif [ $pil = "13" ]
then
    echo $i "open the script......"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/Gameye98/OSIF
    cd OSIF
    ls
    echo $i"installing requeriments....."
    pip2 install -r requirements.txt
    clear
    python2 osif.py
elif [ $pil = "14" ]
then
    echo $i "open the script......."
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/DH4CK1/msfinstall
    cd msfinstall
    ls
    clear
    sh msf.sh
elif [ $pil = "15"
then
    echo $i "open the script......"
    sleep 1
    clear
    cd $HOME
    git clone https://github.com/kadal15/LazyGo-v1
    cd LazyGo-v1
    ls
    clear
    sh lazygo
elif [ $pil = "00" ]
then
    clear
    echo $cy"Terima kasih telah menggunakan tools saya :)"
    echo $cy"semoga bermanfaat!"
    sleep 3
else
    clear
    echo $me"Maaf input anda salah!"
    echo $ne"Silahkan input yg benar!"
    sleep 3
    sh installer2.sh
fi
