# openvpn

 coppy install_and_add.sh\
 chmod +x install_and_add.sh\
 ./install_and_add.sh\
 follow manual:\
    choose UDP (recommended)\
    port - standart\
    DNS - choose Google\
    create your dirst client.\
 systemctl start openvpn-server@server.service\
 systemctl enable openvpn-server@server.service


if you need new client, again start script and choose Add New client
