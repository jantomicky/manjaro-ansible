# Manjaro Playbook

## Update
```
sudo pacman-mirrors && sudo pacman -Syyuu
```

## Requirements
```
sudo pacman -S ansible
```

## Playbook
```
ansible-playbook playbook.yml -i localhost --ask-become-pass --extra-vars="user_name={username}" --skip-tags {desktop|laptop}
```

## NordNM
```
sudo nordnm update --credentials && sudo nordnm sync -a cz normal udp
```

## Finish
```
reboot
```
