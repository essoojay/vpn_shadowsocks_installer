Make all as root! (or use sudo before every command)

commands for installation:

``git clone https://github.com/codesshaman/vpn_shadowsocks_installer.git``

``cd vpn_shadowsocks_installer``

``chmod +x shadowsocks-all.sh``

If your use .deb distribution, you can install all necessary requirements with script:

``chmod +x prepare_deb.sh``

``./prepare_deb.sh``

After that, start main script:

``./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log``