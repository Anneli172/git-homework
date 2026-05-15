## Minu kogemus

### Mis oli keeruline?
[Mergemine]

### Mis oli "ahaa!" hetk?
[gitis mitme haru lisamine]

### VSCode vs käsurida
Kumba kasutaksid igapäevaselt ja miks?
[Kasutaksin käsurida]

### Pull Request workflow
Miks see on parem kui otse main-i push-ida?
[turvaline ja läbipaistev]


sudo mkdir -p /etc/postgresql/16/main/tls
cd /etc/postgresql/16/main/tls

sudo openssl req -new -x509 -nodes -days 365 \
  -out server.crt -keyout server.key

sudo chmod 600 server.key
sudo chmod 644 server.crt
