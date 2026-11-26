# Trabalho-de-Programa-o-Orientada-a-Objetos---SENAC-2-periodo
entreda dos arquivos para a avaliação pedida pelo professor referente a start-up que vai ser desenvolvida
BoaRotaBuss — Gestão de Parceiros e Cupons (POO + MVC + DAO)
Módulo desenvolvido para a startup BoaRotaBuss (plataforma de gestão de transporte rodoviário e turismo), implementando o CRUD completo de duas tabelas relacionadas (PARCEIRO e CUPOM) em PHP Orientado a Objetos com arquitetura MVC e padrão DAO.
Integrantes
Laércio Mateus de Andrade Oliveira — R.A.: 9125
Tecnologias Utilizadas
PHP 8.x (Orientado a Objetos, Namespaces e Autoload)
MySQL 8.0 / MariaDB com driver PDO
HTML5 & CSS3 (Interface responsiva)
Git & GitHub
Como Executar o Projeto
Clone este repositório ou extraia a pasta no diretório do servidor local (ex: htdocs do XAMPP).
Inicie os serviços Apache e MySQL no painel do XAMPP.
Abra o phpMyAdmin ou MySQL Workbench e execute o script database/banco.sql.
Caso o seu MySQL utilize senha no usuário root, ajuste a variável $senha em src/Model/Conexao.php.
Acesse no navegador: http://localhost/BoaRotaBuss/Public/index.php.
Screenshots
(Adicione aqui 1 ou 2 prints da tela funcionando quando testar no laboratório)
Transparência de IA
Ferramentas de Inteligência Artificial (Gemini) foram utilizadas como apoio técnico, didático e de revisão ao longo da evolução do projeto integrador BoaRotaBuss:
Etapa Anterior (Disciplina de Front-End): Auxílio na estruturação das páginas iniciais em HTML/CSS/PHP, padronização da identidade visual, responsividade dos layouts e ajustes de interface do ecossistema da startup.
Etapa Atual (Disciplina de Programação Orientada a Objetos): Reaproveitamento e adaptação da base visual desenvolvida anteriormente para a nova arquitetura orientada a objetos, com apoio da IA para:
Estruturar o modelo base (boilerplate) das classes de conexão e persistência (DAO com PDO e consultas preparadas prepare/execute);
Refatorar e separar as responsabilidades entre as camadas Model, View e Controller (MVC);
Revisar o tratamento de exceções (PDOException), validações de entrada e a documentação deste README.md.
Toda a concepção do negócio da startup BoaRotaBuss, a modelagem das entidades e relacionamentos (PARCEIRO e CUPOM), a execução dos testes no banco de dados e a apresentação em vídeo foram conduzidas pelo autor.
