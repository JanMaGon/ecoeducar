# 🌱 EcoEducar

Sistema web desenvolvido como Trabalho de Extensão do curso de **Tecnólogo em Análise e Desenvolvimento de Sistemas** da **UNINTER**.

O projeto tem como objetivo promover a educação ambiental por meio de um portal informativo sobre descarte responsável de resíduos, oferecendo conteúdos educativos, notícias, programas ambientais e informações sobre locais de descarte.

---

## 🎯 Objetivo

O EcoEducar foi criado para facilitar o acesso da comunidade a informações sobre sustentabilidade e descarte correto de resíduos, incentivando a conscientização ambiental e a participação da população em ações educativas.

Além do portal público, o sistema possui um painel administrativo para gerenciamento de conteúdos e usuários.

---

## ✨ Funcionalidades

### Site público

- Página inicial responsiva
- Blog de notícias
- Informações sobre descarte responsável
- Programas educativos
- Página institucional
- Formulário de contato
- Locais de descarte
- Área "Participe"

### Painel administrativo

- Login de usuários
- Controle de permissões
- Cadastro e gerenciamento de usuários
- Cadastro de posts do blog
- Gerenciamento dos conteúdos do site
- Atualização das informações exibidas ao público

---

## 🛠 Tecnologias utilizadas

### Back-end

- PHP 8+
- CodeIgniter 4

### Front-end

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- jQuery

### Banco de dados

- MySQL

---

## 📁 Estrutura do projeto

```text
app/
public/
writable/
tests/

.env
composer.json
spark
```

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/JanMaGon/ecoeducar.git
```

### 2. Entre na pasta

```bash
cd ecoeducar
```

### 3. Instale as dependências

```bash
composer install
```

### 4. Configure o ambiente

Copie o arquivo:

```text
env
```

para

```text
.env
```

Configure:

- Banco de dados
- URL da aplicação
- Ambiente (`CI_ENVIRONMENT`)

### 5. Execute as migrations (caso existam)

```bash
php spark migrate
```

### 6. Inicie o servidor

```bash
php spark serve
```

A aplicação ficará disponível em:

```
http://localhost:8080
```

---

## 📚 Contexto acadêmico

Este projeto foi desenvolvido como Trabalho de Extensão do curso de Tecnologia em Análise e Desenvolvimento de Sistemas da UNINTER.

Os Objetivos de Desenvolvimento Sustentável (ODS) contemplados são:

- ODS 4 – Educação de Qualidade
- ODS 11 – Cidades e Comunidades Sustentáveis

---

## 📸 Telas

- Página Inicial
- Sobre o Projeto
- Blog
- Locais de Descarte
- Programas Educativos
- Painel Administrativo

---

## 👩‍💻 Autora

**Janise Machado Gonçalves**

- GitHub: https://github.com/JanMaGon

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos.
