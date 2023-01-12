# Dados tratados no Excel.

## Passo a passo referente a manipulação das planilhas em Excel.

1 – Download dos dados, os dados foram separados em duas pastas, a primeira com dados originais e a segunda com dados para manipular.

2 – Criado uma coluna com “duracao_passeio”, realizado o calculo da duração de cada viagem subtraindo a coluna “hora_começo” da coluna “hora_finalização”, formatado a coluna como HH:MM:SS usando Formato > Células > Personalizado > [h]:mm:ss.

3 – Criado uma coluna para identificar o dia da semana, comando usado DIA.DA.SEMANA(C2;1), 1 = Domingo e 7 = Sábado.

4 – Nos dias 07/11/21, 05/03/22, 07/06/22, 26/07/22, 27/08/22 e 08/09/22 as datas de começo e final foram invertidas, corrigido as datas na planilha. 

5 – Incluído aba de prévia estatística para análise individual dos meses de OUT/21, DEZ/21 MAR/22 e JUL/22 (diferentes estações do ano), inserido estatística descritiva de duracao_passeio Dados > Análise de Dados > Estatística Descritiva.
       Inserido Modo dos dias da semana, fórmula =MODO(dia_da_semana).
       Inserido planilha dinâmica para verificar média de duracao_passeio x Membro.
       Inserido planilha dinâmica para verificar média de duracao_passeio x Membro X dia_da_semana.
       Inserido planilha dinâmica para verificar contagem de utilização por Membros x dia_da_semana.

6 – Em algumas planilhas as datas de Início e Final estavam invertidas, usamos a formula =(C2<=D2) para identificar.
