# Exercício 9.1.a — Hello World com Flask

Aplicação simples desenvolvida em Python com Flask para o exercício 9.1.a da disciplina de Engenharia de Software.

## Objetivo

Criar uma aplicação web que exiba a mensagem “Hello World” no navegador, praticando a configuração e a execução de um projeto Flask.

## Tecnologias utilizadas

- Python
- Flask
- Visual Studio Code

## Como executar

Com o Python instalado, abra a pasta do projeto no VSCode e execute os comandos no terminal.

### 1. Criar o ambiente virtual

```bash
python -m venv .venv
```

### 2. Ativar o ambiente virtual no Windows

No PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Instalar o Flask

```bash
python -m pip install Flask
```

### 4. Iniciar a aplicação

Considerando que o arquivo principal seja `app.py`:

```bash
python -m flask --app app run
```

### 5. Acessar no navegador

Abra:

http://127.0.0.1:5000

Com a aplicação em execução, a página exibirá a mensagem definida no código.

## Autora

Sophia Betoni  
Engenharia da Computação — Universidade Presbiteriana Mackenzie