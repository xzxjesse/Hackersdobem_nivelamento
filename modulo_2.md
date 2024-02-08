# Identificar Componentes de Hardware de Computadores

## Aula 01 – Grandezas computacionais e sistemas numéricos

### Grandezas computacionais
    são os aspectos que caracterizam a capacidade e o desempenho dos sistemas de computadores

- Teoria de Booler: Lógica utilizada pelos computadores
- Máquina de Turing: Base teórica para computadores

### Grandezas numéricas:    
- Bit (b): binary digit - 0 ou 1;
- Byte (B): conjunto de 8 bits - representa caracteres;

### Outras grandezas
- Grandezas de armazenamento
- Grandezas de velocidade de transmissão
- Grandezas elétricas

### Bases numéricas:
- Decimal (10)
0, 1, 2, 3, 4, 5, 6, 7, 8, 9

- Hexadecimal (16)
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A(10), B(11), C(12), D(13), E(14), F(15)

- Binária (2)
0, 1

**Notação posicional**<br>
    transforma binários e hexadecimais em decimais<br>
6238 = 6000 + 200 + 30 + 8<br>
6238 = 6x1000 + 2x100 + 3x10 + 8x1<br>
6238 = 6x10^3 + 2x10^2 + 3x10^1 + 8x10^0<br>

**Binário para decimal**<br>
111100012 = 1x27 + 1x26 + 1x25 + 1x24 + 0x23 + 0x22 + 0x21 + 1x20<br>
111100012 = 1x128 + 1x64 + 1x32 + 1x16 + 0x8 + 0x4 + 0x2 + 1x1<br>
111100012 = 128 + 64 + 32 + 16 + 1<br>
111100012 = 241<br>

**Hexadecimal para binário**<br>
FACA16 = F (1111) A (1010) C (1100) A(1010)<br>
FACA16 = 1111 1010 1100 1010<br>

**Decimal para binário**<br>
125/2 = 62, resto 1<br>
62/2 = 31, resto 0<br>
31/2 = 15, resto 1<br>
15/2 = 7, resto 1<br>
7/2 = 3, resto 1<br>
3/2 = 1, resto 1<br>
125 = 111101<br>

## Aula 02 – Arquitetura de hardware: CPU, placa mãe, memória, BIOS

### Componentes de um Computador
- Processador
- Placa-Mãe
- Cooler
- Memória RAM
- HDD/SSD
- Fonte
- Placas Offboard

**CPU (Central Processing Unit):** processardados e transformar em informação<br>
- Frequência
- Núcleos
- Cache
- Arquitetura:
X86 (32 bits) - CISC<br>
X64 (64 bits)- CISC<br>
ARM – RISC<br>
- Nomeclatura

**Placa-mãe:** placa principal onde são conectados todos os componentes do computador<br>
Integração e coordenação de hardware<br>
Componentes: onboard e offboard<br>
- Socket – Processador
- Slot Memória
- Slot PCIe
- Chipset
- Bateria BIOS/UEFI
- BIOS
- Conector 24 pinos – Energia
- Conector 8 pinos – Energia CPU
- Conector SATA
- M.2 (SATA / NVMe)

**Memórias:** armazenar os dados de um sistema, responsável pela velocidade de utilização e troca de dados de um computador<br>
- Não Voláteis
**ROM** (PROMs, EPROMs, EEPROMs, Memória flash): **Memória somente de leitura**<br>
Armazenamento em massa (Pendrive, SSD, HD)<br>
- Voláteis
**RAM** (SIMM, DIMM, SDR, DDR, DDR2, DDR3, DDR4, DDR5, etc): **Memória primária em um computador**<br>
Cache (L1, L2, L3)<br>
Vídeo (GDDR3, GDDR4, GDDR5, GDDR6, HBM, HBM2)<br>
<br>
- Memórias de Vídeo: utilizadas pelas placas de vídeo
<br>
<br>

- **BIOS** (Basic Input Output System): chip na placa-mãe responsável por verificar todos os componentes do computador na inicialização
- **UEFI** (Unified Extensible Firmware Interface): é mais moderna e tem mais recursos que a BIOS tradicional

### Processo de Inicialização

1. Computador é ligado no botão de power;
2. CPU executa instruções de inicialização e envia para os
registradores
3. CPU acessa memória ROM onde está a BIOS/UEFI
4. CPU executa a BIOS/UEFI
5. BIOS/UEFI faz o POST > Se estiver tudo OK
6. BIOS/UEFI carrega o Sistema Operacional na RAM

**POST (Power-On Self-Test)** - verificações:
- Processador
- Memória
- Placa de vídeo
- USBs conectadas
- Teclado
- Discos (HD, SSD ou pendrive)
- Relógio do sistema
- Se houve alteração