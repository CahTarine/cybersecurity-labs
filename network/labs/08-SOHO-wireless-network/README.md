# 🛜 Laboratório SOHO — Configuração de uma Rede de Pequeno Escritório

<br> 

## Objetivo

Construir e configurar uma pequena rede de escritório (SOHO — Small Office/Home Office), integrando dispositivos cabeados e sem fio.

Durante o laboratório, configurei uma rede Wi-Fi protegida, utilizei DHCP para o endereçamento automático dos dispositivos e validei a conectividade entre os equipamentos da rede.

<br>

## Contexto

Realizei este laboratório durante meus estudos de redes e cibersegurança no programa Mujer Digital, utilizando o Cisco Packet Tracer.

O cenário representa um pequeno escritório com computadores, impressora e dispositivos móveis conectados a uma rede local, com acesso cabeado e sem fio.

<br> 

## Procedimento

### 1. Montagem da topologia

Criei a topologia utilizando:

- 1 roteador wireless WRT300N
- 1 modem a cabo
- 1 Cloud-PT para representar a conexão com o provedor
- 2 computadores
- 1 impressora de rede
- 1 notebook
- 1 smartphone

Conectei os dispositivos cabeados ao roteador utilizando cabos Copper Straight-Through e estabeleci a conexão entre a Cloud-PT, o modem e o roteador.

### 2. Configuração da rede sem fio

Configurei o WRT300N para utilizar uma rede Wi-Fi própria para o escritório.

- Defini um SSID personalizado.
- Ativei a segurança WPA2 Personal.
- Configurei uma senha para proteger o acesso à rede.

Em seguida, conectei o smartphone à rede Wi-Fi utilizando WPA2-PSK.

### 3. Configuração do notebook

Substituí a interface de rede cabeada do notebook pela placa wireless WPC300N.

Depois, utilizei o aplicativo PC Wireless para localizar a rede Wi-Fi, realizar a conexão e autenticar o dispositivo.

### 4. Configuração do DHCP

Utilizei o servidor DHCP integrado ao WRT300N para distribuir automaticamente endereços IP aos dispositivos da rede.

Configurei os computadores e a impressora para obter suas configurações de rede por DHCP.

Também verifiquei o recebimento automático dos endereços nos dispositivos sem fio após a conexão com a rede.

### 5. Teste de conectividade

Utilizei o comando `ipconfig` para verificar os endereços atribuídos aos dispositivos.

Em seguida, executei um teste de conectividade utilizando `ping` entre um computador e a impressora.

O teste confirmou a comunicação entre os dispositivos dentro da rede local.

<br>

## Análise

Durante o laboratório, observei na prática como um roteador wireless residencial pode concentrar diferentes funções de uma pequena rede.

O WRT300N atuou como:

- roteador;
- switch para os dispositivos cabeados;
- ponto de acesso wireless;
- servidor DHCP.

Também observei a diferença entre dispositivos conectados por cabo e por Wi-Fi, mantendo todos os equipamentos dentro da mesma rede local.

A utilização do DHCP simplificou a configuração dos hosts, pois os dispositivos receberam automaticamente suas informações de rede sem a necessidade de configurar manualmente cada endereço IP.

A configuração do WPA2 também demonstrou a importância de proteger a rede sem fio contra conexões não autorizadas.

<br>

## Evidências

### Topologia e demonstração de conectividade

![DEMO](https://private-user-images.githubusercontent.com/186188158/638912374-94d66ca0-a715-473f-90ab-f2c455a9f261.gif?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODcyMzc0ODAsIm5iZiI6MTc4NzIzNzE4MCwicGF0aCI6Ii8xODYxODgxNTgvNjM4OTEyMzc0LTk0ZDY2Y2EwLWE3MTUtNDczZi05MGFiLWYyYzQ1NWE5ZjI2MS5naWY_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwODIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDgyMFQxNDQ2MjBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hYmU2ZmI1ZTMyOTE1MzUxOWI5N2ZhOTdkM2I2ZDM2ZTBmYzY3MGMyN2YyMGI4MWQ3MGFmYmM4MTNlZmQ5YTU5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZnaWYifQ.HyllFSBtL1KTxwsMlIsXRs_JHZbBDXAjuqDOOmJvtjo)

<br>

## Conceitos praticados

- Redes LAN
- Redes SOHO
- Roteamento
- DHCP
- Endereçamento IPv4
- Gateway
- Wi-Fi
- WPA2
- WPA2-PSK
- SSID
- Conectividade de rede
- Cisco Packet Tracer

<br>

## Aprendizados

Com este laboratório, aprendi a montar uma pequena rede utilizando dispositivos cabeados e sem fio e a configurar um roteador wireless para atender diferentes funções da rede.

Também pratiquei a configuração de segurança básica para uma rede Wi-Fi e entendi como o DHCP automatiza o endereçamento dos dispositivos.

Por fim, utilizei o `ping` e o `ipconfig` para verificar as configurações e testar a comunicação entre os dispositivos.
