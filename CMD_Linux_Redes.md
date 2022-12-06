# COMANDOS LINUX - RED

## 1. Set static IP on your linux device to connect to your LAN using `nmcli` command

Cambiar dirección IP:

`nmcli connection modify NatAttack ipv4.addresses 192.168.1.55/24`

Cambiar puerta de enlace:

> nmcli con mod NatAttack ipv4.gateway 192.168.1.1

Cambiar DNS:

`nmcli con mod NatAttack ipv4.dns 192.168.1.1`

Cambiar a red estática:

`nmcli con mod NatAttack ipv4.method manual`

Aplicar cambios/reiniciar servicio de red:

`systemctl restart network.service`

o

`nmcli con up NatAttack`

![a](./img/1.png)

## 2. Disable network interface with `nmcli`

## 3. Activate the `nmcli` network interface

## 4. Check with the `ip` command your configuration

## 5. Do ping to nodes on your network

## 6. Lists all .txt files in the current directory and then counts those .txt files and saves the output to a new file

## 7. Create a file from scratch on Linux and include the following information

## 8. Copy it from another host on your network

## 9. Connect to the other host and verify that it has been created

## 10. Download from ubuntu website page the ISO with `wget` command and `curl` command

## 11. Download and confirm that the downloaded file is correct (SHA256SUM) from the same page