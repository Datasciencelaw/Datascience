# Checkout de Presença do Módulo 4 - Aprendizado de Máquina Não Supervisionado

Este repositório contém um notebook do Google Colab que demonstra aplicações práticas de aprendizado de máquina não supervisionado, utilizando o algoritmo K-means para clustering de dados de habitação.

## Descrição

O notebook realiza as seguintes etapas:

1. **Upload e Verificação do Arquivo**:
   - Upload do arquivo de dados.
   - Verificação se o arquivo foi carregado corretamente.

2. **Análise Exploratória de Dados (EDA)**:
   - Exibição de informações gerais sobre o dataset.
   - Estatísticas descritivas das variáveis.

3. **Pré-processamento dos Dados**:
   - Seleção das colunas relevantes para o clustering.
   - Tratamento de valores nulos preenchendo com a mediana.
   - Normalização dos dados.

4. **Determinação do Número Ótimo de Clusters**:
   - Utilização do método do cotovelo para determinar o número ótimo de clusters.

5. **Aplicação do Algoritmo K-means**:
   - Aplicação do K-means com o número ótimo de clusters.
   - Adição dos rótulos dos clusters ao dataset original.

6. **Análise dos Clusters**:
   - Cálculo dos valores médios das características para cada cluster.
   - Exibição da análise dos clusters.

7. **Salvamento dos Dados Clusterizados**:
   - Salvamento dos dados clusterizados em um novo arquivo CSV.
   - Download do arquivo CSV no Google Colab.

## Requisitos

- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `sklearn`

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

- **Clusters Identificados**: 4
- **Análise dos Clusters**: Valores médios das características para cada cluster.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

### Exemplo de `requirements.txt`

```txt
pandas
numpy
matplotlib
scikit-learn
```

### Como Adicionar o README ao Novo Galho no GitHub

1. Crie um novo galho (branch) no seu repositório:
   ```bash
   git checkout -b novo-galho
   ```

2. Crie um arquivo chamado `README.md` no diretório raiz do seu repositório.
3. Copie e cole o conteúdo acima no arquivo `README.md`.
4. Adicione e faça commit do arquivo ao seu repositório:
   ```bash
   git add README.md
   git commit -m "Adiciona README ao novo galho"
   git push origin novo-galho
   ```

