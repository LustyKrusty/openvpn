# openvpn

1 - coppy install_and_add.sh
2 - chmod +x install_and_add.sh
3 - ./install_and_add.sh
4 - follow manual:
    choose UDP (recommended)
    port - standart
    DNS - choose Google
    create your dirst client.
5 - systemctl start openvpn-server@server.service
6 - systemctl enable openvpn-server@server.service


if you need new client, again start script and choose Add New client
