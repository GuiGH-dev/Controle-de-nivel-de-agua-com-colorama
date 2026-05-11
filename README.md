# Controle de Nível de Água

Esse projeto foi desenvolvido como uma atividade prática para simular o monitoramento de um reservatório de água utilizando Python.

A ideia é simples: representar diferentes níveis de água e mostrar no terminal uma mensagem correspondente para cada situação, usando cores para facilitar a visualização.

## 💡 Como funciona

O sistema trabalha com 5 níveis de água:

* Nível 1: Muito baixo (situação crítica)
* Nível 2: Baixo
* Nível 3: Médio
* Nível 4: Alto
* Nível 5: Muito alto (alerta)

Cada nível é exibido com uma cor diferente no terminal, seguindo uma lógica de atenção (do vermelho até o azul).

## Tecnologias utilizadas

* Python
* Biblioteca Colorama (para cores no terminal)

## Estrutura do código

* Uma lista armazena as mensagens dos níveis
* Uma função define qual cor será usada para cada nível
* Um laço percorre os níveis e exibe as mensagens no terminal

---
