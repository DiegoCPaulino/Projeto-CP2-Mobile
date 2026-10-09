
# Contador de Pessoas

Projeto acadêmico da disciplina de **Mobile**, desenvolvido com **React Native**.

## 1. Descrição do projeto

O **Contador de Pessoas** é um aplicativo mobile simples que permite controlar a quantidade de pessoas presentes em um ambiente.

A interface terá um contador exibindo o total de pessoas e dois botões:

- **Entrada (+):** adiciona uma pessoa ao contador.
- **Saída (-):** remove uma pessoa do contador.

O contador não poderá ficar com um valor negativo.

## 2. Onde estará o gerenciamento de estado?

O gerenciamento de estado ficará no componente principal, no arquivo **`App.js`**, utilizando o hook **`useState`** do React.

A variável de estado **`contador`** armazenará a quantidade atual de pessoas. Sempre que esse valor mudar, a informação exibida na tela será atualizada automaticamente.

## 3. Onde estará a função lógica do sistema?

A lógica do sistema também ficará no arquivo **`App.js`**, por meio de duas funções:

- **`incrementar()`**: aumenta o valor do contador em 1 quando o usuário pressiona o botão **Entrada (+)**.
- **`decrementar()`**: diminui o valor do contador em 1 quando o usuário pressiona o botão **Saída (-)**, desde que o contador seja maior que zero.
