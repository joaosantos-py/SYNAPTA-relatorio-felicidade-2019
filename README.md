# SYNAPTA | Relatório Mundial de Felicidade (2019)

## Sobre o projeto

Este projeto analisa a felicidade de 156 países em 2019. O objetivo é comparar os países com maiores e menores notas e observar quais indicadores têm mais relação com a felicidade.

Pergunta principal: quais indicadores estão mais relacionados às maiores pontuações de felicidade?

## Dados utilizados

- Base: World Happiness Report, arquivo `2019.csv`.
- Fonte geral do relatório: https://worldhappiness.report/ed/2019/
- Página do dataset no Kaggle: https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download.
- O arquivo `2019.csv` deve ser baixado no Kaggle. Por cautela, o CSV não é redistribuído neste repositório.

O arquivo reúne a posição no ranking (`Overall rank`), o país (`Country or region`), a nota de felicidade (`Score`) e seis indicadores: PIB per capita, apoio social, expectativa de vida saudável, liberdade de escolha, generosidade e percepção de corrupção.

## Ferramentas

- Google Colab e Python
- Pandas
- Matplotlib
- Seaborn

## Etapas da análise

1. Carregamento do arquivo e conferência das colunas.
2. Verificação de dados ausentes, duplicados, negativos e zerados.
3. Cálculo de estatísticas, incluindo média e mediana.
4. Comparação dos dez países com maiores e menores pontuações.
5. Correlação de Pearson entre o `Score` e seis indicadores.
6. Gráficos e comparação das médias entre os dois grupos.
7. Conclusões e limitações.

## Principais resultados

- A Finlândia apresentou a maior pontuação (7,769) e o Sudão do Sul, a menor (2,853).
- A média do `Score` foi aproximadamente 5,407 e a mediana, 5,380.
- O PIB per capita teve a maior correlação com a felicidade (0,794), seguido da expectativa de vida saudável (0,780) e do apoio social (0,777).
- A generosidade apresentou a menor correlação linear (0,076).
- Os dez países mais felizes tiveram médias maiores nos seis indicadores analisados.

Correlação não comprova causa e efeito.

## Como executar

1. Baixar o arquivo `2019.csv` da página de origem indicada acima.
2. Abrir `SYNAPTA_relatorio_felicidade_2019_versao_final.ipynb` no Google Colab.
3. Selecionar Ambiente de execução > Executar tudo.
4. Quando solicitado, enviar o arquivo `2019.csv` com esse nome.
5. Aguardar as tabelas e os gráficos aparecerem.

O Colab já costuma disponibilizar as bibliotecas utilizadas. Em um ambiente Python próprio, instalar as dependências com `pip install -r requirements.txt`. O notebook contém a etapa de upload específica do Colab.

## Limitações

A análise considera somente 2019 e compara os dez países de cada extremo do ranking. Seis registros com zeros foram mantidos porque seu significado não foi confirmado. Diferenças culturais e métodos de pesquisa também podem influenciar a interpretação dos resultados.

## Sugestão para estudos futuros

Comparar outros anos para verificar se renda, saúde e apoio social continuam associados às maiores pontuações de felicidade.

## Identificação

- Candidato: João Mayco Santos da Silva
- Instituição: UNINASSAU Maceió
- Projeto escolhido: Análise do Relatório Mundial de Felicidade

- ## Uso de Inteligência Artificial

Durante o desenvolvimento deste projeto, foi utilizado o ChatGPT como ferramenta de apoio ao aprendizado e à elaboração do relatório.

A ferramenta auxiliou na compreensão dos conceitos de análise de dados e na revisão dos textos.

O código e os resultados foram testados por mim, João, no Google Colab, assim como a verificação das análises realizadas.




Vale ressaltar que o uso de inteligência artificial se deu pela necessidade de estudos e que esse projeto rendeu varias horas de serviço e escrita por mãos humanas, apesar do auxilio da i.a ter sido muito bem vindo nessa etapa de aprendizado.


