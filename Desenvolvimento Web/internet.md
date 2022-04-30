**Provedores de acesso** (empresas telefonicas) que contratam sinal do **Backbone** ('espinhas dorsais' q gerenciam conexões) e repassam serviços ao usuário final. Serviços como (Provedor de serviço):
- Dial-up (conexão em forma discada)
- ADSL (banda larga)
- fibra ótica
- internet via rádio
- comunicação por satélite
- móvel
- P2P (peer to peer)

- SMS 
msg txt
* não tem custo de envio SMS pra operadora de telefonia! celular troca (cte e naturalmente) alguns bits com as torres de comunicação

- MMS 
msgs multimídia


**servidor DNS** transforma endereço www em **nº IP**
- o nº IP 127.0.0.1 local host é endereço da máquina local

> descobrir endereço de sites usando o terminal :
> tecla Windows + R  (cmd)
> digitar ping <site www....>
> aparece nº IP do site, tempo do dado ir da origem ao destino (latência em ms)

## Classes de redes 

## Velocidade Internet
- 1 Byte = 8 bits
Mbps
- upload (Mbps)
- latência (ms)

## Modem (MOdulator-DEModulator)
HW converte dados que possam ser enviados e lidos entre computadores

## Roteador 
aparelho distribui internet ou pode fazer comunicação entre redes

## Switch
distribui internet para dispositivo que solicitou (não é como roteador q distribui para qualquer um)

## Conexões móveis
- 1G: analógico, velocidade internet 10 kbps (quilobits- 1000 bits/s)
- 2G ou GSM: digital, 97 kbps, com acesso internet ou ligação (não dava pra usar ao msm tempo) . *GSM Global System for Mobile Communication*
- GPRS (General packet radio service): 32-80 kbps com transmissão de dados e voz (ao msm tempo)
- EDGE *Enhanced data rates for GSM evolution* 128-236 kbps
- 3G : 7 Mbps (megabits/s, 7 milhões)
- 4G : 22,1 Mbps
- 5G : 10 Gbps (gigabits/s, 10 bilhões)

## TCP/IP

- protocolos de comunicação entre computadores
- TCP (transmission control protocol - protocolo de controle de transmissão), IP (internet protocol)
- usa modelo de camadas, ou seja, pra comunicar passa pelas camadas FÍSICA (1), REDE (2), TRANSPORTE(3), APLICAÇÃO (4)

1- FÍSICA - placa de rede,cabo de rede, wireless,..
2- REDE - IP,..

3-TRANSPORTE - TCP e UDP > já estão configurados qd conecta (modem, roteador,provedor já sabe)
- **UDP**: conexão rápida, não confiável (não tem confirmação de entreg de pacotes) -> usado em livestream

- **TCP**: voltado à conexão, handshake (confirma entrega -> intgridade e ordem de dados) -> usado em aplicativos de msgs

4- APLICAÇÃO - FTP, SMTP, HTTP ...

- **Ports** (porto) portas por onde sairão e chegarão dados. Portas como: 
FTP(20, files), 
SSH (22, conexão segura entre computadores), 
SMTP (25, emails), 
DNS (53,tradutor do nome para nº IP), 
HTTP(80, requisição simples), 
HTTPS(443, requisição segura)
* Gmail  costuma usar portas próprias, que não as padrões SMTP e POP3. Quais são ??????
* B.D como MySQL e servidor web como Apache - Quais portas usadas por estes sistemas??????


# Domínio

# Wi-fi
- IEEE define padrões, dentre eles está pra Wi-fi

## Segurança na Internet
os +famosos:
- WEP: chaves(senhas) 64 bits e 128 bits
- WPA: chave trocada periodicamente
- WPA2 (camada de AES) traz + segurança mas requer +processamento

## Dispositivos na rede
impressora, chromecast, scanner...

## Bluetooth
faz conexão ponto a ponto sem depender da internet

- classes: 1 (potência 100mW com alcance 100m), 2 (2,5mW, alcance 10m), 3 (1mW, alcance 1m apenas)

- versões do Bluetooth

# Browser
- Browser identifica várias LP, lingugens de Marcação e conteúdo multimidia
- plugins/add-ons nos browsers q ajudam a navegação
- pra acessar a Internet sem browser precisaria de um pgma q interprete LP 

# Página Estática e Dinâmica
- Sites (pgs da internet) podem ser feitas em diversas LP. 

> Antes sites sem mta interação - HTML (linguagem de marcação e ñ de pgmç)
> https://web.archive.org/web/
> Hj vários elementos independentes- D/XHTML

- há SWs executados no navegador (Aplicativos -apps).  Um app celular é uma espécie de navegador. 
- Está caindo em desuso o termo 'site'. Não há mta diferença entre:
     - **SITE** e **APLICATIVO** (hj são sites com funções de app) e
     - **SW , PGMA e APP**

***
# Historia

- 1º **email** (eletronic email, correio eletronico)


## site mais antigo em atividade?
- nordu.net criada em 1º janeiro 1985 pela agência NORDUnet (sediada na Dinamarca) conecta redes pesquisa e educação dos países nórdicos
- primeiro dominio "pontocom" registrado no dia 15 de março de 1985 foi o Symbolics.com pela empresa Symnolics que criava computadores corporativos com linguagem Lisp.  No Brasil, o 1ºdomínio é 
- info.cern.ch em 20 dezembro de  com 'tutorial' de como usar a nossa maravilhosa www. 

## blogs
"diário" - posts
- 1º blog
## vlogs 
diário em forma de vídeo

## 1ª compra feita pela Internet
 

## Hist arqs gifs, jpg, png 
formatos de imgs ; png e gif aceita transparencia ; jpg pra fotos menores perde qualidade,resolução

**pixel** = picture + element, quadradinhos q compõe a img

## Formato de musica
mp3

## Qd surgiu emoticons / emojis?

## Surgimento dos memes

# Links 
[Museu Historia da Internet symbolics.com](https://symbolics.com/museum/)

[www cern browser](https://worldwideweb.cern.ch/browser/)

# Fontes

https://www.uol.com.br/tilt/colunas/pergunta-pro-jokura/2021/09/06/qual-e-o-site-mais-antigo-da-internet.htm