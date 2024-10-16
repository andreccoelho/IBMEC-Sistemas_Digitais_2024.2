# Memorial Descritivo

## Título: Somador Paralelo/Serial
### Integrantes:
- André Costa Coelho - 202208385371
- Michel Lutegar D'Orsi Pereira - 202208385192

## Descrição Geral
Este projeto consiste em um somador paralelo de dois números binários de 4 bits. A saída é indicada por LEDs, e a soma paralela pode ser convertida para uma sequência serial com o uso de chaves de seleção e botões. A proposta inclui um subtrator de 4 bits utilizando um somador binário.

## Componentes Utilizados

| **Componente**                       | **Fabricante/Código**   | **Função**                                  | **Quantidade** |
|--------------------------------------|------------------------|---------------------------------------------|---------------|
| 4-Bit Binary Adder with Fast Carry  | DM74LS283              | Realiza a soma de dois números binários de 4 bits com propagação rápida de carry, essencial para garantir somas precisas e rápidas. | 1             |
| 8-lnput Data Selector/Multiplexer   | MC74HC151              | Seleciona uma entre oito entradas binárias e a direciona para a saída, sendo usado para a conversão da saída paralela para serial no projeto. | 1             |
| LED Amarelo                         | -                      | Indica visualmente o resultado da soma binária (0 = apagado, 1 = aceso). | 6             |
| LED Vermelho                        | -                      | Sinaliza a sequência serial (aceso = 1, apagado = 0). | 1             |
| Dip Switch                          | -                      | Chaveia manualmente as entradas binárias (A e B) para o somador de 4 bits. | 2             |
| Push-Button                         | -                      | Controla a saída serial dos bits somados para o LED vermelho. | 2             |
| Protoboard                          | -                      | Plataforma usada para montagem e teste do circuito. | 1             |

---

### Observações:
1. **4-Bit Binary Adder with Fast Carry (DM74LS283)**:  
   Esse componente é fundamental para somar rapidamente dois números binários de 4 bits, garantindo que a propagação do carry entre os bits seja eficiente. Ideal para sistemas digitais que exigem rapidez nas operações aritméticas.

2. **8-lnput Data Selector/Multiplexer (MC74HC151)**:  
   O multiplexador é utilizado para selecionar, entre as saídas paralelas da soma, quais bits serão enviados de forma serial para o LED vermelho. Essa seleção é feita com o auxílio dos botões push-button.
