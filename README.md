# 🌙 WakeCraft 🌙
A Minecraft proxy that will automatically start your server when someone joins, and put it to sleep when nobody is connected.
🚧 This is still a prototype ! AND CODE IS UGLY. 🚧

## How to use it
Do not use it in production, it's not ready yet.
1. Download the binary for your platform from the [releases page](https://github.com/shadowdevfr/wakecraft/releases/)
2. Run it with `./wakecraft <port> <your mc server directory> "<start command>"`
3. For example, if my Minecraft server is in directory "server" and I start it with "java -jar server.jar", I will run `./wakecraft 25565 server "java -jar server.jar"`. The proxy will then listen to connections on port 25565 and start the server when someone connects.