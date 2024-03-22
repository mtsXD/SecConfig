### 𝗦𝗢𝗕𝗥𝗘
Aqui vamos deixar seu unix fantasma, utilizando configurações Tor e Privoxy.<br>
Resumindo...
- &nbsp; Fazer sua maquina funcionar toda como Tor.
- &nbsp; Melhorar sua segurança do seu navegador.
- &nbsp; Alterar o seu IP para algum local da europa.

É uma configuração que melhora sua privacidade enquanto navega, peço por favor, para não entrar em 𝘀𝗶𝘁𝗲𝘀 𝗽𝗿𝗼𝗶𝗯𝗶𝗱𝗼𝘀 ou fazer 𝗮𝗰̧𝗼̃𝗲𝘀 𝗶𝗹𝗲𝗴𝗮𝗶𝘀. 

### 𝗣𝗿𝗶𝗺𝗲𝗶𝗿𝗼 𝗽𝗮𝘀𝘀𝗼
𝙄𝙣𝙨𝙩𝙖𝙡𝙖𝙘̧𝙖̃𝙤 𝙙𝙤 𝙜𝙪𝙛𝙬 
<br>
Antes de mais nada, é sempre bom dá aquele update e upgrade, lembrese de estar no modo 𝗿𝗼𝗼𝘁:
```
apt update && apt upgrade -y
```
Caso o terminal retorne algum erro, tente fazer a seguinte alteração:
```
apt update && apt upgrade -y --fix-missing
```
Apos ter dado aquela atualizada, é só instalar o gufw:
```
apt install gufw
```
Apos isso, é só executar ele no terminal digitando o comando:
```
gufw
```

<br>
𝙘𝙤𝙣𝙛𝙞𝙜𝙪𝙧𝙖𝙘̧𝙤̃𝙚𝙨 do 𝙜𝙪𝙛𝙬

<br>

Com a interface gráfica da aplicação aberta, por medidas de segurança faça as seguintes alterações:
<br>

1º Ative o status do software.<p>
2º Rejeite os dados de entrada e saída, conforme está na figura abaixo.<p>
3º Vá para a aba 𝙍𝙪𝙡𝙚𝙨 e faça as configurações que serão mostradas posteriomente.
<br>

<img align="center" src="https://github.com/mtsXD/SecConfig/blob/main/IMG/gufw.png"/>
<br>



<img align="center" src="https://github.com/mtsXD/SecConfig/blob/main/IMG/gufw%20Rules.png"/>
