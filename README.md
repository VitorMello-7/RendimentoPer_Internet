Projeto feito para teste e aprendizado da biblioteca SidraPy.

Escolhi uma tabela bem simples de usar a 7419 que se encontra no site da Sidra onde estão vários dados históricos do IBGE.
A tabela 7419 se refere a pesquisa "Rendimento médio mensal real domiciliar per capita em domicílios que havia utilização da Internet, por equipamento utilizado para acessar a Internet", classificada por regioẽs no ano de 2021.

Para entender a capacidade da biblioteca SidraPy decidi aplica-la juntamente com outras bibliotecas para testar sua integração, utilizei Pandas e Seaborn, para uma análise exploratória e plotar gráficos.
O resultado foi excelente e ainda fui capaz de tirar alguns insights.

Para iniciar uma consulta em Python com a SidraPy, o primeiro passo é utilizar o comando [sidrapy.get_table()] e passar alguns parâmetros da tabela.
