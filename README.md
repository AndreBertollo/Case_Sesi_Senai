# Case_Sesi_Senai

## Desafio Proposto

O Serviço Social da Indústria (SESI) e o Serviço Nacional de Aprendizagem Industrial
(SENAI) são duas empresas paraestatais pertencentes ao “Sistema S”. Em ambas as empresas,
grande parte da arrecadação provem da contribuição social dos trabalhadores de setores
classificados como industriais (No caso, deverão contribuir para o SESI e SENAI os
trabalhadores das empresas classificadas como pertencentes ao FPAS 507 (setores industriais)
e não optantes do simples). Logo, análises sobre a dinâmica da arrecadação de ambas
empresas passam diretamente pela compreensão da dinâmica do mercado de trabalho.
Dentre os conjuntos de dados com informações relevantes a compreensão do mercado de
trabalho formal, destaca-se a Relação Anual de Informações Sociais (RAIS). Em tese, todas as
empresas e instituições que possuem vínculos empregatícios deverão declarar informações
demográficas e salariais de seus trabalhadores à RAIS. Uma vez que as informações são
declaradas, espera-se que erros ocorram por parte das empresas. Sendo assim, a partir de uma
amostra da RAIS (fornecida em anexo), responda:
 Demonstre a distribuição dos salários da CBO com maior massa salarial (soma de
salários) dos contribuintes para o SESI SENAI. Há “outliers” nessa distribuição? Se sim,
esses outliers podem ser classificados como erros de declaração?
Para tanto, utilize os dois arquivos em anexo. O primeiro arquivo (rais.csv) é uma amostra
dos dados da RAIS. Essa amostra apresenta as seguintes informações:
 Salário mensal do indivíduo (valor_remuneracao_media);
 CNAE no nível de subclasse da empresa em que o indivíduo atua (cnae_2_subclasse);
 CBO da ocupação do indivíduo (cbo_2002);
 Dummy para a empresa em que o individuo atua é optante do simples
(indicador_simples) (1 = optante; 0 = não optante)
O segundo arquivo contém os CNAE a nível de subclasse classificados como pertencentes
ao FPAS 507.
