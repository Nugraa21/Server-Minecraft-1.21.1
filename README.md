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