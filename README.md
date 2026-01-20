# Server-Minecraft-1.21.1

```bash
sudo apt update && apt upgrade
```
## copy salah satu link versi yang kalian inginkan di web ini
[Versi minecraft](https://gist.github.com/osipxd/6119732e30059241c2192c4a8d2218d9)
- untuk start server:     java -Xmx8G -Xms4G -jar paper.jar --nogui

### cmd install playit.gg (bisa langsung buka web playit.gg seperti di video)
```bash
curl -SsL https://playit-cloud.github.io/ppa/key.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/playit.gpg >/dev/null
echo "deb [signed-by=/etc/apt/trusted.gpg.d/playit.gpg] https://playit-cloud.github.io/ppa/data ./" | sudo tee /etc/apt/sources.list.d/playit-cloud.list
sudo apt update
sudo apt install playit
```

# CONTOH

```BASH 
wget "https://fill-data.papermc.io/v1/objects/7e8fd35b554aea8d1492c83fcf429e9c8e391464e50f82ee3e408be87b4e80df/paper-1.21.11-39.jar"
```

abis itu ganti nama jadi paper

```bash
java -Xmx8G -Xms4G -jar paper.jar --nogui
```