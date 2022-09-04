# Anvils Raw Programme
Anvils is a community! and we cannot make anvils without you, so come, help us, test our beta releases, try them, test them, and report the bugs, Welcome Anvils 2.0 Raw DREAMER!
[Download 2.0-1 Raw](https://drive.google.com/file/d/1qy8uc82xfh3gdpTyM1uN-KLNve4feuEb/view?usp=sharing)

# Note in the Latest Release of Anvils Raw 2.0-1
The tweak tool is broken as i forgot to add a dependency *nala*, please use these commands to install nala before using the tweak tool

## Add Nala Repos
```echo "deb https://deb.volian.org/volian/ scar main" | sudo tee /etc/apt/sources.list.d/volian-archive-scar-unstable.list
wget -qO - https://deb.volian.org/volian/scar.key | sudo tee /etc/apt/trusted.gpg.d/volian-archive-scar-unstable.gpg > /dev/null
```

## Install Nala
```
sudo apt update && sudo apt install nala
```
