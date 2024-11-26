# Memorial Descritivo  

## Título: Somador Paralelo/Serial  
### Integrantes:
- André Costa Coelho - 202208385371  
- Michel Lutegar D'Orsi Pereira - 202208385192  

---

## Descrição Geral  
Este projeto consiste em um somador paralelo de dois números binários de 4 bits. A saída é indicada por LEDs, incluindo um LED azul para sinalizar o carry da soma. A soma paralela é convertida para uma sequência serial com o uso de um contador crescente cíclico baseado em flip-flops JK e um multiplexador. O projeto também inclui um subtrator de 4 bits, implementado por meio de complemento de 2.  

---

## Componentes Utilizados  

| **Componente**                       | **Fabricante/Código**   | **Função**                                  | **Quantidade** |
|--------------------------------------|-------------------------|---------------------------------------------|---------------|
| 4-Bit Binary Adder with Fast Carry   | DM74LS283               | Realiza a soma de dois números binários de 4 bits com propagação rápida de carry. | 1             |
| Flip-Flops JK                        | 74LS76                  | Implementam o contador crescente cíclico usado na conversão paralela para serial. | 2             |
| 8-lnput Data Selector/Multiplexer    | MC74HC151               | Seleciona uma entre oito entradas binárias para a saída serial. | 1             |
| LED Amarelo                          | -                       | Indica visualmente os bits da soma binária. | 4             |
| LED Azul                             | -                       | Indica o carry da soma binária.             | 1             |
| LED Verde                            | -                       | Sinaliza a sequência serial (aceso = 1, apagado = 0). | 1             |
| Dip Switch                           | -                       | Chaveia manualmente as entradas binárias (A e B) para o somador de 4 bits. | 2             |
| Resistores                           | -                       | Protegem os LEDs e realizam debounce nas entradas. | 10            |
| Placa Universal Perfurada            | -                       | Protótipo final para montagem do circuito.  | 1             |
| Gerador de Clock                     | -                       | Gera o sinal de sincronismo para o contador crescente cíclico. | 1             |

---

### Observações:  

1. **4-Bit Binary Adder with Fast Carry (DM74LS283):**  
   Este componente realiza a soma binária de forma eficiente, com uma propagação rápida do carry entre os bits.  

2. **Flip-Flops JK (74LS76):**  
   Essenciais para o contador crescente cíclico, que converte os dados da saída paralela para serial.  

3. **8-lnput Data Selector/Multiplexer (MC74HC151):**  
   Seleciona os bits da saída paralela para transmiti-los de forma serial, controlando o fluxo de dados para o LED verde.  

4. **LED Azul:**  
   Indica o estado do carry, fornecendo uma sinalização adicional para validar a soma.  

5. **Placa Universal Perfurada:**  
   Permite a montagem e teste do circuito final antes da construção em uma PCI dedicada.  
