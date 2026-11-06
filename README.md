# Rede neural do CS231n em NumPy

Reprodução do código do slide 30 da aula **Neural Networks and Backpropagation**, de Fei-Fei Li, Yunzhu Li e Ruohan Gao (Stanford, 2023). O notebook contém o treino, os resultados e as verificações usadas no relatório PDF entregue à parte.

[Abrir no Google Colab](https://colab.research.google.com/github/mh131105/cs231n-rede-neural/blob/main/rede_neural_cs231n.ipynb) · [Slides](https://cs231n.stanford.edu/slides/2023/lecture_4.pdf)

## Rodar no computador

Com Python 3.11 ou superior, execute na pasta do repositório:

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install numpy==2.3.5 matplotlib==3.10.7 jupyterlab
python -m jupyterlab rede_neural_cs231n.ipynb
```

No Windows, ative o ambiente com `.venv\Scripts\activate`.

Selecione o kernel **Python 3** e use **Restart Kernel and Run All**. No Colab, use **Executar tudo**. O notebook gera os dados, fixa as sementes e dispensa arquivos externos e GPU. No Colab, se faltar uma dependência, execute `%pip install numpy==2.3.5 matplotlib==3.10.7` em uma célula antes dos imports.

Testado com Python 3.12.12, NumPy 2.3.5 e Matplotlib 3.10.7. Outras versões e processadores podem alterar os últimos dígitos dos resultados.
