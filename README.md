# LH_CD_RafaelLima
Desafio Cientista de Dados 

# Projeto de Previsão de Preço de Imóveis

Este projeto utiliza um modelo de **Regressão Linear** para prever os preços de imóveis com base em variáveis como localização, tipo de imóvel, número de avaliações, entre outras. O modelo foi treinado usando um conjunto de dados e agora pode ser utilizado para fazer previsões com base em novos exemplos de imóveis.

## Bibliotecas Utilizadas

Este projeto faz uso das seguintes bibliotecas:

- **scikit-learn**: para treinamento de modelos de aprendizado de máquina (Regressão Linear).
- **pandas**: para manipulação e análise de dados.
- **numpy**: para operações numéricas.
- **matplotlib** e **seaborn**: para visualização de dados.
- **pickle**: para salvar e carregar o modelo treinado.

## Pré-requisitos - Antes de Colocar a Mão na Massa

Antes de executar o projeto, certifique-se de que você tenha as bibliotecas necessárias instaladas. Você pode instalar as dependências usando o arquivo `requirements.txt` ou manualmente com o comando `pip`.

### Usando o arquivo `requirements.txt`

1. Clone este repositório ou baixe o projeto.
2. Navegue até a pasta onde o projeto está localizado.
3. Execute o seguinte comando para instalar as dependências:
   
```bash
pip install -r requirements.txt
ou 
pip install numpy pandas scikit-learn matplotlib seaborn
```
## Estrutura do Projeto - Olha só como tudo está organizado!

```bash
├── modelo.pkl            # O seu modelo maravilindo salvo aqui
├── requirements.txt      # Para garantir que você não vai esquecer de nada 
├── main.py               # O código principal que faz tudo funcionar
├── data                  # A pasta com os dados (se você tiver dados para compartilhar, né?)
└── README.md             # Este arquivo, cheio de glamour e instruções
