
# Checkout de Presença do Módulo 5 - Aplicações Práticas em Aprendizado de Máquina no Google Colab

Este repositório contém um notebook do Google Colab que demonstra aplicações práticas em aprendizado de máquina, utilizando o dataset de marketing bancário da UCI Machine Learning Repository.

## Descrição

O notebook realiza as seguintes etapas:

1. **Instalação e Importação de Bibliotecas**:
   - Instalação da biblioteca `ucimlrepo` para acessar datasets da UCI.
   - Importação de bibliotecas necessárias como `pandas`, `seaborn`, `matplotlib`, `sklearn`, entre outras.

2. **Carregamento do Dataset**:
   - Utilização da função `fetch_ucirepo` para carregar o dataset de marketing bancário (ID: 222) da UCI.
   - Separação dos dados em features (`X`) e targets (`y`).

3. **Análise Exploratória de Dados (EDA)**:
   - Análise descritiva das variáveis numéricas.
   - Visualização da distribuição da idade dos clientes.
   - Análise da distribuição dos tipos de emprego.

4. **Pré-processamento dos Dados**:
   - Divisão dos dados em conjuntos de treino e teste.
   - Aplicação de `OneHotEncoder` para variáveis categóricas e normalização para variáveis numéricas.

5. **Treinamento do Modelo**:
   - Treinamento de um classificador Random Forest.
   - Avaliação do modelo utilizando métricas como `classification_report` e `roc_auc_score`.

## Requisitos

- Python 3.x
- Bibliotecas: `ucimlrepo`, `pandas`, `seaborn`, `matplotlib`, `sklearn`

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook no Google Colab ou localmente:
   - Google Colab

## Estrutura do Repositório

- `notebook.ipynb`: Notebook do Google Colab com o código completo.
- `requirements.txt`: Lista de dependências necessárias para executar o notebook.

## Resultados

- **Acurácia do Modelo**: 88%
- **ROC AUC**: 0.841

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

### Exemplo de `requirements.txt`

```txt
ucimlrepo
pandas
seaborn
matplotlib
scikit-learn
```

### Como Adicionar o README ao GitHub

1. Crie um arquivo chamado `README.md` no diretório raiz do seu repositório.
2. Copie e cole o conteúdo acima no arquivo `README.md`.
3. Adicione e faça commit do arquivo ao seu repositório:
   ```bash
   git add README.md
   git commit -m "Adiciona README ao repositório"
   git push origin main
   ```

Isso deve ajudar a documentar seu projeto de forma clara e organizada no GitHub. Se precisar de mais alguma coisa ou tiver alguma dúvida, estou à disposição!
