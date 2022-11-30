Snort Installation:

Step 1:
(1) wget https://www.snort.org/downloads/snort/daq-2.0.7.tar.gz
(2) wget https://www.snort.org/downloads/snort/snort-2.9.20.tar.gz
(3) tar xvzf daq-2.0.7.tar.gz              
(4) cd daq-2.0.7
(5) sudo apt-get install git libpcap-dev
(6) ./configure && make && sudo make install
(7) cd ..
(8) tar xvzf snort-2.9.20.tar.gz                 
(9) cd snort-2.9.20
(10) sudo apt-get install libdumbnet-dev
(11) Install Luajit:
    (11a) Go to https://luajit.org/download.html
    (11b) Download LuaJIT-2.1.0-beta3.tar.gz
    (11c) tar zxf /home/szm/Downloads/LuaJIT-2.1.0-beta3.tar.gz
    (11d) cd LuaJIT-2.1.0-beta3
    (11e) make
    (11f) sudo make install
(12) ./configure --enable-sourcefire && make && sudo make install

(13) Download snort3-community-rules.tar.gz from Step 3 in https://www.snort.org/
(14) 

