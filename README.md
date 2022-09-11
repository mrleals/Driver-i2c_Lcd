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
### Com seguinte comando crier um repositorio para o driver do display:
```shell
sudo nano I2C_LCD_driver.py
```
> Na sua raspberry crie um repositorio com o codigo disponibilizado [Aqui](https://github.com/mrleals/Driver-i2c_Lcd/blob/8bf6711d8883edadf162531c6391230666f1da7d/I2C_LCD_driver.py)

### Aperte a tecla Cntrl + S para salvar e logo apos Cntrl + X
Agora crie e use sua imaginacao para escrever o que desejar em seu display
esse primeiro comando usando:
```shell
sudo nano helloworld.py
```

> Use essa programacao [Aqui](https://github.com/mrleals/Driver-i2c_Lcd/blob/40943bc27a05a02c1c4da4b0fb796fe1ce515ab8/helloworld.py)

Disponibilizarei outras programacoes para poder se divertir com seu display

> Doações Paypal
marcovoceali@gmail.com
