# Projeto Somador Paralelo/Serial  

![IMG-20241126-WA0021](https://github.com/user-attachments/assets/2b91711a-678c-4dae-b1eb-8e551615d976)

## Disciplina: Sistemas Digitais  
**Equipe:** André Costa & Michel Lutegar  

**Professor:** Clayton J A Silva  

---

### Descrição Geral  
Este projeto tem como objetivo desenvolver um sistema digital que realiza a soma de dois números binários de 4 bits e converte o resultado em uma saída serial utilizando um contador crescente cíclico. O sistema também utiliza LEDs para sinalização do resultado da soma e da sequência serial, e *Dip Switches* para configurar os números binários de entrada.

---

### Funcionalidades  
1. Soma dois números binários de 4 bits utilizando um somador paralelo.  
2. Apresenta o resultado da soma binária em LEDs amarelos e um LED azul.  
3. Converte a saída paralela da soma em uma sequência serial com base em um contador crescente cíclico.  
4. Utiliza um LED verde para indicar o estado da saída serial (aceso = 1, apagado = 0).  
5. Configura os números de entrada usando *Dip Switches*.  

---

### Componentes Utilizados  
- **Dip Switches:** Entrada de números binários de 4 bits.  
- **Somador Paralelo:** Realiza a operação de soma.  
- **Contador Crescente Cíclico (Flip-Flops JK):** Controla a conversão paralela para serial.  
- **Multiplexador (MUX):** Realiza a seleção da saída paralela para serial.  
- **LEDs Amarelos:** Indicam os bits da soma.
- **LEDs Azul:** Indica o carry da soma.   
- **LED Verde:** Sinaliza a sequência serial na saída.  
- **Resistores:** Proteção dos LEDs e debounce dos *Dip Switches*.  
- **Placa Universal Perfurada:** Protótipo final do sistema.  
- **Gerador de Clock:** Gera o sinal de sincronismo para o contador.


---

### Artefatos Entregues  
1. **Memorial Descritivo:**  
   - Relação completa dos componentes utilizados, incluindo modelo, fabricante, função e quantidade.  
   - Descrição detalhada do funcionamento do sistema, revisando o conteúdo proposto na AP1.  

2. **Esquema do Circuito:**  
   - Elaborado no EasyEDA, incluindo entradas e saídas lógicas, alimentação e conexões do contador.  

3. **Protótipo:**  
   - Protótipo funcional construído em placa universal perfurada.

---


**Data de Entrega:** 27 de novembro de 2024  
