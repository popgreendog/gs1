#Comandos Úteis

ip -br -c a
nano /etc/network/interfaces

Linux:
C: echo, > (echo "agaragã" > gtasa.txt)
R: cat
U: nano

allow-hotplug [placa3]
  iface [placa3] inet static
    address [IP]

apt install || apt install upgrade
apt install apache2 apach2-utils -y
apt instal net-tools
apt install netcat

netstat-nltp
service apache2 start
systemctl start apache2

python3 -m http.server [Porta]

man netcat | less
nc -v [IP][Porta] | nc -vlp [Porta]

#Locais de interesse

/etc/apache2 -> apache2.conf (Indexes "<Directory/SRV>")
cp apache2.conf apache2.conf.old

/etc/apache2/conf-enabled -> security.conf (Prod + Off)

/var/log/apache2
tail -n[N] access.log
