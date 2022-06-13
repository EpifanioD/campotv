<h1 align="center"> Projeto CampoTv - Teste </h1>

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

# Resumo do projeto
Projeto de um micro gerenciador de notícias, onde o usuário final pode visualizar, editar, apagar, inserir notícios de texto aceitando uma foto referente a notícia. Onde por sua vez ele dá a opção de exportar um arquivo Json ou XML das 3 últimas notícias.

<h4 align="center"> 
    :construction:  Instalação!  :construction:
</h4>

## 🛠️ Abrir e rodar o projeto

- `1° Passo`: Crie um banco de dados com nome "campotv";
- `2° Passo`: Utilizei o WampServer para a conexão com o banco, senha de acesso padrao : usuario: root; senha = '';
- `3° Passo`: Criar a tabela como o exemplo a seguir:

<br>
  CREATE TABLE `campotv`.`news` (
  `id` INT NOT NULL AUTO_INCREMEN,
  `title` VARCHAR(255) NULL,
  `description` VARCHAR(255) NULL,
  `image` VARCHAR(255) NULL,
  `created_at` DATETIME NULL DEFAULT CURRENT_TIMESTAMP,
  `updated_at` DATETIME NULL DEFAULT NULL ON UPDATE CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`));

## ✔️ Técnicas e tecnologias utilizadas

- ``PHP 8``
- ``Axios``
- ``Paradigma de orientação a objetos``
- ``Vuejs``
- ``MVC``
- ``Bootstrap``
