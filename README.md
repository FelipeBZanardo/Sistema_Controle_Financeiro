# Projeto Final - Lógica de Programação II (Python)
> *Turma 11080 - Santander Coders 2024 - Engenharia de Dados*

Desenvolvimento do projeto "Sistema de Controle Financeiro" com o intuito de registrar, alterar, deletar e visualizar movimentações financeiras (Receita, Despesa e Investimento), além de poder exportar relatório final e agrupar os dados em tipo de movimentação, mês, ano ou data.
**Todo projeto foi desenvolvido com a linguagem de programação Python.**

## ✒️Autores 
- [Alessandra Cruz](https://github.com/alessandracruz)
- [Álex Buracosky](https://github.com/aburacosk)
- [Diana Osorio](https://github.com/diana468)
- [Diogo Moura](https://github.com/)
- [Felipe Zanardo](https://github.com/FelipeBZanardo)
- [Thiago Silva](https://github.com/)

## 📋Enunciado do Projeto

### 💸 Projeto Final | Sistema de Controle Financeiro

O sistema deverá ser capaz de realizar as seguintes operações:

- **Criar** novos registros e identificar a data que o registro foi feito, qual tipo de movimentação, valor.

  - Os tipos podem ser:
    - Receita: o valor deve ser tratado como numérico e armazenado normalmente.
    - Despesas: o valor deve ser recebido como positivo, mas armazenado como negativo
    - Investimento: deve ter uma informação a mais de 'Montante', em que será calculado quanto o dinheiro rendeu desde o dia que foi investido.
    Para essa finalidade utilize a seguinte formula: $M = C * (1 + i)^t$ ([Saiba mais](https://matematicafinanceira.org/juros-compostos/)), considere tudo em dias.
- **Ler** registros: Deverá ser possível consultar os registros por data, tipo ou valor.
- **Atualizar** registros: No caso de atualização, pode-se atualizar o valor, o tipo e a data deverá ser a de atualização do registro.
- **Deletar**: Deverá ser possível deletar o registro (caso necessário, considere o indice do elemento como ID)

Outras funcionalidades:
- Crie uma função ```atualiza_rendimento``` que atualize os valores de rendimento sempre que chamada.
- Crie uma função ```exportar_relatorio```, que seja possível exportar um relatorio final em csv ou json.
- Crie pelo menos uma função de agrupamento, que seja capaz de mostrar o total de valor baseado em alguma informação (mes, tipo...)
- Crie valores separados para identificar a data (dia, mes, ano)

---

## Diagrama de Caso de uso:
<p align="center">
  <img src="./diagrama de caso de uso.jpg">
</p>

## Demonstração
<p align="center">
  <img src="./_captures/Demonstracao.gif">
</p>

## 📋  Pré-requisitos
- Ter instalado o **[Python](https://www.python.org/)**;
- Ter instalado uma IDE de sua preferencia:
    - **[Visual Studio Code](https://code.visualstudio.com/)**, por exemplo.
    - **[Google Colab](https://colab.research.google.com/notebook)** (Não é necessário instalação).

## ⚙️ Executar o projeto:
- Fazer o clone do repositório do projeto [Sistema_Controle_Financeiro](https://github.com/FelipeBZanardo/Sistema_Controle_Financeiro);
- Abrir o arquivo **Projeto_LPII.ipynb** na IDE;
- Caso o arquivo **banco_dados.csv** (presente no repositório do projeto) esteja na mesma pasta, Registros iniciais serão carregados para melhor desempenho e teste do projeto;
- Selecionar a opção "Run All" para iniciar todas as funções, inclusive a do menu principal;
- Pronto! Teste o projeto com um menu completamente interativo e intuitivo.

## 🧾 Bibliotecas Python utilizadas

- Biblioteca de Datas:
`from datetime import datetime`

- Biblioteca de NamedTuple:
`from collections import namedtuple`

- Biblioteca para leitura e escrita de arquivos CSV:
`import csv`

- Programação funcional com o uso de Reduce:
`from functools import reduce`

## 🛠️ Tecnologias Utilizadas

* [Visual Studio Code](https://code.visualstudio.com/) - IDE 
* [Python](https://www.python.org/) - Linguagem de Programação

## 📈 Melhorias futuras

- Melhorar a interface gráfica com a interação com o usuário;
- Exportar o relatório para outros formatos, como o JSON ou até mesmo em formatos visuais como o Power BI;
- Aceitar diversos tipos de investimentos;

## 📺 Apresentação
(https://www.canva.com/design/DAGN6v-N5wY/0vncuYt_SkjzmkkjGtA04g/edit)


