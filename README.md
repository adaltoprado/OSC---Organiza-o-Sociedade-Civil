# 🚀 SCFV: Gestão de Vínculos e Frequência

![Badge de Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Badge de Linguagem](https://img.shields.io/github/languages/top/adalitoprado/OSC-Organiza-o-da-Sociedade-Civil)

Este repositório documenta um sistema _web_ com banco de dados criado para fortalecer e gerenciar o **Serviço de Convivência e Fortalecimento de Vínculos (SCFV)**.

O foco principal é auxiliar na gestão de programas voltados para a terceira idade, sendo uma ferramenta de apoio ao trabalho essencial do **Instituto São Paulo em Movimento (OSC)**.

---

## 🎯 O Desafio

Gerenciar um programa social tão vital como o SCFV exige organização. Manter o controle de cadastros, a frequência diária e acompanhar a evolução dos participantes (especialmente da terceira idade) pode ser um desafio complexo feito manualmente.

Este sistema nasceu para **simplificar e centralizar** esse processo!

## ✨ Funcionalidades Principais

O sistema oferece uma plataforma simples para a gestão completa dos participantes:

* **📝 Cadastro de Usuários:** Registro de novos participantes no serviço.
* **🔍 Consulta e Listagem:** Visualização rápida de todos os cadastrados.
* **✏️ Gestão CRUD:** Funcionalidades completas para **C**riar, **L**er, **A**tualizar e **D**eletar (CRUD) registros.
* **📊 Acompanhamento de Presença:** Ferramentas para registrar a frequência e visualizar gráficos de participação.
* **📈 Evolução:** Páginas para acompanhar o desenvolvimento e a participação ao longo do tempo.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com ferramentas clássicas e robustas da web:

* **🐘 PHP:** Para todo o processamento *backend* e lógica do servidor.
* **🗃️ MySQL (ou similar):** Como banco de dados para armazenar todas as informações.
* **📄 HTML5:** Para a estruturação de todas as páginas.
* **🎨 CSS3:** (Para a estilização - *adicione aqui se estiver usando*).
* **🔒 Conexão Segura:** Scripts de conexão (`conexao.php`) e processamento de login para proteger os dados.

## 🏁 Como Rodar o Projeto Localmente

Para testar ou desenvolver este projeto na sua máquina, você precisará de um ambiente de servidor local (como XAMPP, WAMP ou MAMP).

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/adalitoprado/OSC-Organiza-o-da-Sociedade-Civil.git](https://github.com/adalitoprado/OSC-Organiza-o-da-Sociedade-Civil.git)
    ```
2.  **Inicie seu servidor local:** Abra o XAMPP e inicie os módulos **Apache** e **MySQL**.
3.  **Banco de Dados:**
    * Acesse `http://localhost/phpmyadmin`.
    * Crie um novo banco de dados (ex: `scfv_db`).
    * Importe o arquivo `.sql` do projeto (se você tiver um) para criar as tabelas.
4.  **Conexão:**
    * Abra o arquivo `conexao.php` no seu editor de código.
    * Ajuste as credenciais de conexão (`$servidor`, `$usuario`, `$senha`, `$dbname`) para que correspondam ao seu ambiente local.
5.  **Execute:**
    * Mova a pasta do projeto para o diretório `htdocs` (no XAMPP) ou `www` (no WAMP).
    * Acesse `http://localhost/OSC-Organiza-o-da-Sociedade-Civil` no seu navegador.

---

## 👨‍💻 Autores

Este projeto foi desenvolvido com a colaboração de:

* ADALTO DE JESUS PRADO
* ANTONIO MANUEL DA SILVA JUNIOR
* BEATRIZ DA SILVA ALVES
* GABRIELA CRISTINA RIBEIRO
* JOAO OCTAVIO NOBREGA FERREIRA DE SOUZA LIMA
* NILSON BRANDAO
* RENAN LUNARDELI DOS SANTOS
* SUEVALDA RIBEIRO DE SANTANA SILVA

---

## 🤝 Contribuição

Sinta-se à vontade para abrir *issues* ou enviar *pull requests*. Toda ajuda para melhorar a gestão desse serviço tão importante é bem-vinda!
