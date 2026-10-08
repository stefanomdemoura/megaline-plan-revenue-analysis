# Megaline — análise de receita dos planos Surf e Ultimate

Projeto de análise de dados para comparar dois planos pré-pagos de telecomunicações e entender quais características de uso explicam a geração de receita.

## Objetivo

Comparar Surf e Ultimate em chamadas, mensagens, internet e receita mensal por usuário, respeitando as regras de cobrança de cada plano e testando estatisticamente diferenças relevantes.

## Ferramentas

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- Jupyter Notebook

## Principais análises

- preparação de cinco conjuntos de dados;
- consolidação mensal por usuário;
- implementação das regras de cobrança de minutos, mensagens e internet;
- distribuição de uso por plano;
- receita média, mediana, variância e receita total;
- teste t de Welch entre Surf e Ultimate;
- comparação entre NY-NJ e demais regiões.

## Principais achados

- o consumo médio de minutos é muito parecido entre os planos;
- o Surf ultrapassa com maior frequência as franquias, especialmente a de internet;
- o Surf gera maior receita total na amostra, cerca de 95,5 mil, por ter uma base de usuários maior;
- o Ultimate apresenta maior receita média mensal por usuário, cerca de 72,31 contra 60,71 no Surf;
- há evidência estatística forte de diferença entre as receitas médias dos dois planos;
- o resultado para NY-NJ versus demais regiões é significativo a 5%, mas é limítrofe (`p ≈ 0,034`) e deve ser interpretado com cautela.

## Dados

Os datasets não são redistribuídos neste repositório. Para executar o notebook localmente, coloque os arquivos indicados em `data/`.

Os outputs foram mantidos para que a análise possa ser visualizada diretamente no GitHub.
