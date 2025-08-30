if git is not isntalled run

```
sudo apt install git -y
```

paste this in you're linux terminal 

```
apt update && apt install git -y && cd && git clone https://github.com/IYSTREEM/serveo.net-tunnel-script/ && chmod +x serveo.net-tunnel-script/port && mv serveo.net-tunnel-script/port /bin && clear && rm -rf ~/serveo.net-tunnel-script
```
if you're getting any permission denied error run it with suppuer user using "su -i" or try this command

```
sudo apt update && sudo apt install git -y && cd && sudo git clone https://github.com/IYSTREEM/serveo.net-tunnel-script/ && sudo chmod +x serveo.net-tunnel-script/port && sudo mv serveo.net-tunnel-script/port /bin && clear && sudo rm -rf ~/serveo.net-tunnel-script
```
usage

```
   port add <port>
   port remove <port>
   port refresh <port>

```
  
credits to [shadow](https://discord.com/users/1116705678745141339) for the command
