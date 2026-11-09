# 🤖 Automação de Tarefas e Bots (RPA) — Cadastro de Produtos

Este projeto consiste em um script de **Robotic Process Automation (RPA)** desenvolvido em Python durante a **Jornada Python**. A aplicação automatiza todo o processo de login em um sistema corporativo web e o cadastro massivo de centenas de produtos extraídos de uma base de dados em arquivo `.csv`.

---

## 🎯 Objetivo do Projeto

Eliminar tarefas manuais repetitivas de digitação, reduzindo o tempo de execução de cadastros e evitando erros humanos durante a inserção de dados em sistemas web.

---

## ⚡ Funcionalidades

- **Abertura Automática de Sistema Web:** Inicialização do navegador e navegação até a página de login.
- **Autenticação Automática:** Preenchimento de credenciais de acesso (e-mail e senha).
- **Importação de Base de Dados:** Leitura automatizada da tabela `produtos.csv` utilizando a biblioteca **Pandas**.
- **Cadastro em Loop:** Preenchimento automatizado de cada campo do formulário (Código, Marca, Tipo, Categoria, Preço Unitário, Custo e Observações) com suporte ao tratamento de valores nulos (`pd.isna()`).
- **Navegação Inteligente:** Controle do ritmo de automação (`pyautogui.PAUSE`), envio dos dados (`Enter`) e retorno ao topo da página (`Scroll`).

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3** — Linguagem principal.
- **PyAutoGUI** — Automação de comandos de mouse e teclado.
- **Pandas** — Leitura, manipulação e estruturação da base de dados CSV.
- **Time / Webbrowser** — Controle de tempos de espera e gerenciamento de navegação.

---

## 📂 Estrutura do Repositório

- **`codigo.py`**: Script principal com a lógica da automação.
- **`produtos.csv`**: Base de dados contendo a lista de produtos a cadastrar.
- **`README.md`**: Documentação do projeto.

---
