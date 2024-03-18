# Compreender acesso a rede e camada de internet (IP)

## Aula 1 - Camada de acesso

### Modelos de comunicação em camadas:

**- Modelo TCP/IP** <br>
Aplicação<br>
Transporte<br>
Internet<br>
Acesso a rede<br>

**- Modelo OSI** <br>
Aplicação<br>
Apresentação<br>
Sessão<br>
Transporte<br>
Rede<br>
Enlace<br>
Física<br>

## Aula 2 - Endereço MAC e tráfego de Dados

**MAC Adress** - Media Access Control <br>
Endereço exclusivo de um dispositivo de rede, geralmente representado por seis pares de caracteres hexadecimais, separados por dois-pontos.

### Tipos de endereços MAC:

**- Unicast:** B4:45:06:64:ED:9F <br>
**- Broadcast:** FF:FF:FF:FF:FF:FF <br>

## Aula 3 - Protocolo ARP

**Protocolo ARP** - Address Resolution Protocol<br>
Utilizado para mapear endereços IP para endereços MAC em redes locais, conectando um IP em constante mudança a um endereço fixo.

## Aula 04 – Endereçamento IPv4

**Endereço IPv4** - Internet Protocol version 4 <br>
É um sistema de identificação numérica atribuído a dispositivos de rede para permitir a comunicação eficaz dentro de uma rede IP.<br> 
- Estrutura: 4 octetos separados por pontos, onde cada octeto é composto por 8 bits e varia de 0 a 255 (decimal).
<br><br>

**Endereço IP** - Internet Protocol: permite a conectividade entre dispositivos em uma rede<br>
- O endereço IP e a mascara de rede determinam a qual rede o dispositivo pertence;
- A utilização de diferentes máscaras dentro de uma rede, garante a segurança dos usuários dessa rede, fazendo com que cada máscara trabalhe individualmente, sem afetar a velocidades ou desempenho das demais.

## Aula 05 - IP Público, Privado e NAT

- Os **IPs internos/privados** são gerados automaticamente para manter casas ou empresas conectadas. (LANs)
- Os **IPs públicos/externos** são atribuídos pelo provedor de internet contratado pelo cliente. (WANs)
- **NAT** - Network Address Translation é a conversão/tradução de IPs públicos e privados.

## Aula 06 - Sub rede e super rede

- **Sub rede:** É a divisão de uma rede de computadores em segmentos menores.

- **Super rede:** É a combinação de várias redes.