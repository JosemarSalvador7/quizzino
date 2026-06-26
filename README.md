# 🧠 Quizino

<p align="center">
Aplicação Desktop de Quiz desenvolvida com Python para aprendizagem interativa.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3.10+-3776AB?logo=python">
<img src="https://img.shields.io/badge/UI-CustomTkinter-1F6AA5">
<img src="https://img.shields.io/badge/License-GPL-blue">
<img src="https://img.shields.io/badge/Status-Active-success">
</p>

---

## Sobre

O **Quizino** é uma aplicação desktop criada para proporcionar uma experiência de aprendizagem através de perguntas e respostas.

Desenvolvido em **Python + CustomTkinter**, o projeto utiliza perguntas carregadas dinamicamente e um sistema de níveis para tornar cada sessão diferente.

---

## Funcionalidades

* Sistema de níveis (Fácil, Médio e Difícil)
* Perguntas aleatórias
* Pontuação dinâmica
* Interface moderna
* Feedback visual de respostas
* Reinício rápido do jogo
* Compatibilidade multiplataforma

---

## Sistema de Níveis

| Nível   | Questões | Pontos |
| ------- | -------: | -----: |
| Fácil   |        5 |     +1 |
| Médio   |        7 |     +2 |
| Difícil |       10 |     +3 |

---

## Tecnologias

* Python
* CustomTkinter
* OpenPyXL
* Pillow
* Type Hints
* Programação Orientada a Objetos
* Programação Funcional

---

## Estrutura do Projeto

```text
quizzino/
│
├── Quizzino/
├── bases/
├── LICENSE
├── README.md
├── main.py
├── pyproject.toml
└── uv.lock
```

---

## Instalação

### Clonar repositório

```bash
git clone https://github.com/JosemarSalvador7/quizzino.git
cd quizzino
```

### Instalar dependências

Com UV:

```bash
uv sync
```

ou

```bash
pip install .
```

---

## Executar

```bash
python main.py
```

---

## Banco de Perguntas

As perguntas são carregadas através de ficheiros externos.

Exemplo:

| Pergunta          | Opção 1 | Opção 2  | Opção 3 | Opção 4 | Resposta |
| ----------------- | ------- | -------- | ------- | ------- | -------- |
| Capital de Angola | Luanda  | Benguela | Huambo  | Cabinda | 1        |

> A coluna **Resposta** representa o índice da opção correta.

---

## Objetivos

* Praticar desenvolvimento desktop
* Aplicar arquitetura e organização de código
* Explorar interfaces gráficas modernas
* Construir um projeto educativo open source

---

## Licença

Este projeto está licenciado sob a **GNU General Public License (GPL)**.

Pode utilizar, modificar e redistribuir este software, desde que versões derivadas mantenham a mesma licença e disponibilizem o código-fonte.

Consulte o ficheiro **LICENSE** para mais informações.

---

## Autor

**João Salvador Paulo**
Desenvolvedor de Software • Full Stack em formação

Construindo projetos para aprender e evoluir continuamente.
