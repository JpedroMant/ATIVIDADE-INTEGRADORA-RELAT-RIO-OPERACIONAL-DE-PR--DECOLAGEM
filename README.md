# ATIVIDADE-INTEGRADORA-RELAT-RIO-OPERACIONAL-DE-PR--DECOLAGEM
Atividade integradora da fase 1 do 1 ano de Ciencia da computação da FIAP

Esse projeto ilustra um lançamento hipotético de uma nave tripulada para Marte, composto por uma parte teórica e um codigo Python para execução de uma checagem básica dos modulos principáis para que possa ser realizado o lançamento da missão.

Os números ilustrados no CSV e no resultado do exemplo de execução, foram aleatoriamente gerados por uma IA, sem nenhuma relação com a realidade.

o Codigo ira analisar os dados com base nos seguintes parâmetros:
  integridade estrutural (0 ou 1) - 0 = falha,

  temperatura interna (ºC) - qualquer valor acima de 35 = falha,
  
  temperatura externa (ºC) - qualquer valor menor que 60 = falha,
  
  nivel de energia (% da capacidade máxima) - qualquer valor menor que 60 = falha,
  
  pressão do tanque (bar) - qualquer velor menor que 4.0 = falha,
  
  qualquer módulo crítico (0 ou 1) - 0 = falha,

o código irá analisar cada um dos dados fornecidos e retornar "Lançamento Autorizado" caso tudo esteja OK, caso um, ou mais modulos estejam fora dos parametros, retornará "Lançamento não Permitido"

Print da execução CSV 1:

<img width="1599" height="824" alt="image" src="https://github.com/user-attachments/assets/a4d713c2-d75c-4887-ac9b-fead6ab3aa28" />

Print da execução CSV 2:

<img width="1598" height="809" alt="image" src="https://github.com/user-attachments/assets/9b7cad06-4289-405c-a504-41cfd2721f4b" />

O Código funciona com a análise de CSV que é inserido logo no inicio do código, sendo a única alteração necessária para o seu funcionamento.

