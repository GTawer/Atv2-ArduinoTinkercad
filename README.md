# 💡 Desenvolvimento de Sistemas e Lógica de Programação: Desafio do Elevador (6 Andares) 🔌

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

Esta atividade foi desenvolvida no curso **Técnico em Desenvolvimento de Sistemas** utilizando o **Tinkercad**. O desafio consistiu em expandir um sistema de elevador original de 3 andares para um sistema funcional de **6 andares**.

O objetivo foi aprimorar a lógica de controle e a manipulação de múltiplos componentes de entrada (botões) e saída (LEDs) no Arduino.

---

## 📂 Detalhes do Projeto

| Item | Descrição | Status |
| :--- | :--- | :--- |
| `Hardware` | Montagem de 6 LEDs (andares) e 6 botões de chamada no Tinkercad. | ✅ |
| `Lógica de Expansão` | Implementação de movimentação sequencial passo a passo entre todos os andares. | ✅ |
| `Código-Fonte` | Programação em C++ comentada seguindo a estrutura original do projeto. | ✅ |

---

## 🐦‍⬛ Lógica de Expansão

Para atender aos requisitos do desafio, a lógica foi expandida da seguinte forma:
* **Mapeamento:** Adição dos pinos 8, 9 e 10 para LEDs e 2, 3 e 4 para botões.
* **Movimentação Realista:** Diferente da lógica simples, o sistema agora utiliza sequências de `if` dentro de cada `case`. Isso garante que, se o elevador for do 1º ao 6º andar, ele acenda e apague cada LED intermediário por 3 segundos, simulando o deslocamento físico.
* **Controle de Estado:** A variável `atual` é atualizada em cada etapa do percurso, permitindo que o sistema saiba exatamente onde o elevador está para a próxima chamada.

---

## 🔗 Link do Projeto
* [Acesse aqui o projeto no Tinkercad - Gabriel de Araujo Torres](https://www.tinkercad.com/things/6H1Tybntjo4-elevador-de-6-andares)
* [Acesse aqui o projeto no Tinkercad - Gabriel Pereira Dias](https://www.tinkercad.com/things/0MmbqbKCpXb-terrific-luulia)

---

## 🛠️ Ferramentas Utilizadas

* **Tinkercad:** Simulação dos circuitos eletrônicos.
* **Arduino UNO:** Microcontrolador utilizado.
* **Linguagem C/C++:** Programação da lógica de controle.

---

## 👥 Autores

* **Disciplina:** Lógica de Programação (LOPAL)
* **Professores:** Raul Porto Lopes e Paulo Cesar Camargo
* **Alunos:** Gabriel de Araujo Torres (Nº 08) e Gabriel Pereira Dias (Nº 10)
* **Data:** 12/05/2026

#### Projeto desenvolvido no SENAI A. Jacob Lafer.

<p align="">
  <img src="https://media1.tenor.com/m/BY7flZqxkLUAAAAC/scott-pilgrim-scott-pilgrim-vs-the-world.gif" width="200" height="auto" />
</p>
