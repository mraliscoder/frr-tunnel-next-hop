```
    1  apt install git
    2  git clone https://github.com/mraliscoder/frr-tunnel-next-hop
    3  cd frr-tunnel-next-hop/
    4  curl -s https://deb.frrouting.org/frr/keys.asc | sudo apt-key add -
    5  echo "deb https://deb.frrouting.org/frr $(lsb_release -s -c) frr-stable" | sudo tee /etc/apt/sources.list.d/frr.list
    6  sudo apt update
    7  apt-cache madison libyang2-dev
    8  apt insatll libyang2-dev
    9  apt install libyang2-dev
   10  sudo apt-get install    git autoconf automake libtool make libreadline-dev texinfo    pkg-config libpam0g-dev libjson-c-dev bison flex    libc-ares-dev python3-dev python3-sphinx    install-info build-essential libsnmp-dev perl    libcap-dev libelf-dev libunwind-dev    protobuf-c-compiler libprotobuf-c-dev
   11  sudo apt-get install devscripts equivs
   12  nno debian/control 
   13  nano debian/control 
   14  nano debian/frr.install 
   15  nano debian/frr.ru
   16  nano debian/rules 
   17  sudo mk-build-deps --install debian/control
   18  ./bootstrap.sh
   19  dpkg-buildpackage -us -uc -b
   20  cd ..
   21  ls -la
   22  curl -T frr_10.5-dev_amd64.dev
   23  curl -T frr_10.5-dev_amd64.deb
   24  curl -T frr_10.5-dev_amd64.deb bashupload.com
   25  ls -la
   26  curl -T frr-pythontools_10.5-dev_all.deb bashupload.com
   27  nano frr/
   28  cd frr-tunnel-next-hop/
   29  nano bgpd/bgp_route.c 
   30  dpkg-buildpackage -us -uc -b
   31  curl -T ../frr_10.5-dev_amd64.deb bashupload.com
```
