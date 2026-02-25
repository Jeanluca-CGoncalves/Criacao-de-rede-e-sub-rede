# Projeto Prático Cisco - Criação de Redes e Sub-redes

Este repositório contém os arquivos e documentações referentes ao "Projeto Prático Cisco" desenvolvido na disciplina de Gerência de Redes (Engenharia de Computação)
## 📌 Escopo do Projeto

O objetivo principal deste projeto é demonstrar a compreensão sobre o formato e a semântica dos números IPv4, cálculo de redes e sub-redes, configuração de hosts, configuração de roteadores e implantação de serviços de rede[cite: 100, 101]. [cite_start]A infraestrutura de rede foi desenhada para conectar múltiplas localidades simuladas (IFSuldeMinas, DME e Prysmian)[cite: 119, 135, 183].

### 🛠️ Requisitos e Funcionalidades Implementadas

**Redes Cabeadas:** Construídas com atribuição de endereçamento IPv4 estático nas LANs especificadas
   Todas as LANs estão identificadas com nome, endereço IP de rede (E.R.), Primeiro Host Válido (P.H.V.), Último Host Válido (U.H.V.), Endereço de Broadcast (E.B.) e Máscara de Rede (M.R.
**Roteamento:** Os roteadores possuem configurações estáticas, porém o roteamento adotado é dinâmico, permitindo a comunicação entre todas as sub-redes. As interfaces ativas estão devidamente identificadas * **Serviços de Rede:**
    **Servidores Web:** Habilitados e configurados com IPv4 estático nas respectivas redes 
    **Serviço DNS:** Instalado e configurado centralmente (`100.100.100.100`) para resolver nomes de domínio, permitindo que as máquinas acessem os servidores Web através de URLs ao invés de IPs
    **Serviço DHCP:** Implementado em uma LAN específica (LAN DHCP - `172.0.0.0`) para distribuição automática de endereços IP para os hosts locais (ex: PC1-DHCP a PC5-DHCP)
## 💻 Tecnologias e Ferramentas

**Simulador:** Cisco Packet Tracer 
**Protocolos:** IPv4, DHCP, DNS, HTTP, Protocolos de Roteamento Dinâmico 

## 🚀 Como Visualizar a Simulação

Para abrir e visualizar este projeto, você precisará do software **Cisco Packet Tracer** instalado em sua máquina.

1.  Clone este repositório.
2.  Abra o arquivo `.pkt` utilizando o Cisco Packet Tracer
3.  Aguarde a convergência da rede (as luzes dos links devem ficar verdes).
4.  Realize testes de conectividade (Ping) entre os PCs de diferentes LANs.
5.  Acesse o navegador web de qualquer PC e tente acessar os servidores através das URLs configuradas no DNS.
