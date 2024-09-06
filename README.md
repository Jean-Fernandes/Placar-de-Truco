# projeto Placar de Truco

- o placar deve ser capaz de apresentar as seguintes informações:
	- Pontuação da dupla A (0 a 12)
	- Pontuação da dupla B (0 a 12)
	- quantidade de tenteos da dupla A (0 a 3)
	- quantidade de tenteos da dupla B (0 a 3)
- o sistema possui duas entradas, destinadas a adcionar pontos aos times:
	- a entrada Ba adciona 1 ponto ao time A.
	- a entrada Bb adciona 1 ponto ao time B.
- quanto atingir 12 pontos, zera-se a pontuação da dupla e incrementa-se um tento;
- quando a dupla atingir 3 tentos, ela ganha a partida e o sistema para, esperando o sinal de reset;
- considere que os botões não são síncronos com o relógio;
- apresentar o resultado em display de sete segmentos.
esse projeto deve ser feito em systemverilog para ser implementado na FPGA (EP4CE115F29C7)
