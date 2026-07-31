# 🛜 Configuração do DHCP em um Roteador Wireless

## Objetivo

Configurar um roteador wireless para fornecer endereços IP automaticamente aos clientes da rede por meio do DHCP, alterando a faixa de endereçamento e verificando a conectividade entre os dispositivos.

## Cenário

Foi simulada uma rede doméstica composta por um roteador wireless e três computadores conectados por cabos Ethernet.

A atividade teve como foco a configuração do endereço IP do roteador, a alteração da faixa de endereços disponibilizada pelo DHCP e a configuração dos computadores para obter seus endereços IP automaticamente.

## Habilidades praticadas

- Configuração de endereço IPv4 em um roteador wireless
- Configuração de DHCP
- Definição de faixa de endereços DHCP
- Configuração automática de clientes via DHCP
- Verificação de configurações de rede com `ipconfig`
- Teste de conectividade com `ping`
- Identificação do gateway padrão
- Configuração de uma rede local

## Conceitos estudados

- DHCP (Dynamic Host Configuration Protocol)
- Endereço IPv4
- Gateway padrão
- Faixa de endereçamento IP
- Endereçamento dinâmico
- Roteador wireless
- Comunicação entre dispositivos em uma rede local
- `ipconfig`
- `ping`

## Resultado

O roteador wireless foi configurado com o endereço `192.168.5.1` e o servidor DHCP foi ajustado para distribuir endereços a partir de `192.168.5.126`, com limite de 75 usuários.

Os três computadores foram configurados para obter seus endereços automaticamente por DHCP e os testes de conectividade entre os dispositivos e o roteador foram realizados com sucesso.
