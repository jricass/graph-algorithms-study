# Estudo e Implementação de Algoritmos de Caminhamento em Grafos

Este repositório contém o código-fonte e a documentação para o projeto de **Estudo, Pesquisa e Implementação de Algoritmos de Caminhamento em Grafos**.

O objetivo é implementar e analisar algoritmos clássicos de busca e caminho mínimo em grafos, demonstrando seus mecanismos de funcionamento aplicados a cenários práticos de **logística, navegação e sistemas financeiros**, sem o uso de bibliotecas prontas para a lógica dos algoritmos.

## 📋 Algoritmos Implementados

Os seguintes algoritmos foram abordados neste projeto:

1.  **BFS (Busca em Largura)**
    *   **Arquivo**: `src/BFS.ipynb`
    *   **Características**: Exploração em camadas utilizando estrutura de fila (FIFO).
    *   **Aplicação Prática**: Mapeamento de zonas de entrega em logística.

2.  **DFS (Busca em Profundidade)**
    *   **Arquivo**: `src/DFS.ipynb`
    *   **Características**: Exploração profunda com backtracking utilizando recursão.
    *   **Aplicação Prática**: Auditoria de conectividade em redes de transporte.

3.  **Dijkstra (Caminho Mínimo)**
    *   **Arquivo**: `src/Djkistra.ipynb`
    *   **Características**: Algoritmo para grafos com pesos não-negativos.
    *   **Aplicação Prática**: Navegação urbana (sistemas GPS).

4.  **Bellman-Ford (Caminho Mínimo com Pesos Negativos)**
    *   **Arquivo**: `src/Bellman-Ford.ipynb`
    *   **Características**: Suporta pesos negativos e detecta ciclos negativos.
    *   **Aplicação Prática**: Cálculos financeiros entre contas interdependentes.

## 🚀 Como Executar

Este projeto utiliza **Jupyter Notebooks** para combinar código, explicações e visualizações.

### Pré-requisitos

Certifique-se de ter o Python instalado. As dependências do projeto são:

*   `jupyter`
*   `networkx`
*   `matplotlib`

Você pode instalar as dependências executando:

```bash
pip install jupyter networkx matplotlib
```

### Executando os Notebooks

1.  Clone este repositório:
    ```bash
    git clone https://github.com/jricass/graph-algorithms-study.git
    cd graph-algorithms-study
    ```

2.  Abra o VS Code ou o terminal na pasta do projeto e inicie o Jupyter:
    ```bash
    jupyter notebook
    ```
    Ou utilize a extensão do Jupyter no VS Code para abrir os arquivos `.ipynb` diretamente na pasta `src/`.

3.  Execute as células dos notebooks para ver as demonstrações de funcionamento e visualização dos algoritmos.

## 📂 Estrutura do Projeto

```
graph-algorithms-study/
├── src/
│   ├── BFS.ipynb          # Implementação da Busca em Largura
│   ├── DFS.ipynb          # Implementação da Busca em Profundidade
│   ├── Djkistra.ipynb     # Implementação do Algoritmo de Dijkstra
│   └── Bellman-Ford.ipynb # Implementação do Algoritmo de Bellman-Ford
└── README.md              # Documentação do projeto
```

## 👤 Autores

*   João Ricardo Silva de Almeida
*   Felipe Gabriel Souza Libório 

## 📝 Requisitos do Projeto

*   **Implementação Manual**: Uso de estruturas de dados básicas.
*   **Operações**: Implementação completa dos algoritmos.
*   **Visualização**: Plotagem gráfica dos grafos utilizando NetworkX (apenas para visualização).
*   **Volume de Dados**: Testes com grafos de 16 vértices.
*   **Cenários Práticos**: Aplicação dos algoritmos em problemas reais.