## 1. Separação de Prioridades

Alta Prioridade (MVP)

Menu principal funcional com todas as opções previstas.

Cadastro e listagem de despesas.

Cadastro e listagem de tipos de despesa (em arquivo texto).

Cadastro e login de usuários com criptografia de senha.

Estrutura básica de classes (POO): Despesa, Usuario, TipoDespesa, Pagamento.

Armazenamento e leitura de dados a partir de arquivos .txt.

Média Prioridade

Edição e exclusão de despesas.

Filtros de listagem (por período, status e categoria).

Implementação de interfaces e herança entre categorias de despesa.

Contagem estática de despesas criadas.

Baixa Prioridade (Versões Futuras)

Interface gráfica (JavaFX / PHP com HTML).

Relatórios formatados e gráficos.

Exportação de dados (CSV, PDF).

Testes automatizados e refatoração.

## 2. POC (Prova de Conceito)

A POC tem como foco validar o funcionamento dos arquivos de armazenamento e a estrutura orientada a objetos.
Serão testados:

Criação e leitura de arquivos de texto (usuarios.txt, despesas.txt, tipos.txt).

Criação de objetos das classes principais (Despesa, Usuario).

Serialização simples de dados (gravar e ler com fopen, fwrite, fread).

Menu em execução com System.out.println() (simulação de fluxo principal).

Resultado esperado: validação da persistência de dados e da execução dos métodos básicos de CRUD.

##3. Projeto do MVP

O MVP (Produto Mínimo Viável) será composto por:

Menu principal funcional.

Cadastro e listagem de despesas.

Cadastro de tipos de despesa.

Cadastro e login de usuários (criptografia).

Armazenamento em arquivos .txt.

Estrutura POO com herança e polimorfismo básico.

O objetivo é entregar uma versão funcional que já permita inserir, listar e gerenciar dados básicos, validando o modelo lógico do sistema e a arquitetura proposta.

## 4. Estrutura Inicial de Pastas
/src
├── main/
├── MenuPrincipal.java
├── Usuario.java
├── Despesa.java
├── TipoDespesa.java
├── Pagamento.java
    └── interfaces/
    └── Pagavel.java
 ├── data/
     ├── usuarios.txt
     ├── despesas.txt
     └── tipos.txt
/docs
 ├── README.md
 └── CHANGELOG.md
