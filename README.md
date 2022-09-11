# Driver-i2c_Lcd
> Lcd i2cLcd na raspberry pi
### Primeiro passo
> Ativar as configuracoes I2c na raspberry
para isso abra o termina da raspberry e digite:
```shell
sudo raspi-config
```
Vá até as opções avançadas: "Advanced Settings"
> selecione a opção:
```shell
I2C Enable/Disable automatic loading
```
### instale o driver i2c-tools com comando:
```shell
get install i2c-tools
```
### instale os drivers do python com:
```shell
sudo apt-get install python-smbus
```
### Digite o comando:
> Para identificar o endereço central do seu LCD
```shell 
i2cdetect -y 1
```
# Programando o LCD 

