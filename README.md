# VC-X Solutions - Code Challenge

[**VC-X Solutions**](https://vcx.solutions/) é uma startup do Grupo Senior Sistemas, sediada em
Florianópolis, SC. Nascemos com o propósito de impactar positivamente o mercado e entregar
facilidades em meio a processos complexos. Hoje, oferecemos uma plataforma completa — VC-X Sonar —
que já ajudou centenas de empresas a descomplicar a telecom e TI. E quer saber? Estamos só começando
e vamos revolucionar o mercado, oferecendo soluções cada vez mais automatizadas, conectadas e
eficientes.

Nosso time de desenvolvimento é composto por desenvolvedores apaixonados pelo que fazem. Priorizamos
processos de desenvolvimento ágeis e melhores práticas, oferecendo um ótimo ambiente para
profissionais que amam o que fazem.

## Objetivo

Este repositório contém um desafio usado para avaliar as habilidades dos candidatos no
desenvolvimento Full Stack.

É importante notar que resolver o problema de forma satisfatória é apenas uma parte da avaliação.
Também consideramos outras disciplinas de programação, como documentação, testes, histórico de
commits e melhores práticas de codificação.

## Como Participar

1. Leia atentamente as especificações para entender completamente o problema e todos os requisitos
antes de começar;

1. **Faça um fork deste repositório** no Github. Se você não puder criar um fork público, crie um
repositório privado e conceda acesso de leitura aos seguintes usuários:
    - `gustavo.rosa@vcx.solutions`;
    - `hugo.santos@vcx.solutions`.


## Especificação

Você deve implementar uma aplicação para gestão de inventário de ativos de TI.
Esta aplicação deve permitir que os usuários possam **cadastrar**, **visualizar**, **listar** e **remover**
equipamentos de TI.

O objetivo é avaliar sua capacidade de desenvolver tanto o backend quanto o frontend da aplicação.

### Backend

O backend deve fornecer uma API que permita realizar as operações de CRUD
(Create, Read, Update, Delete) para gerenciar os ativos.

#### Funcionalidades da API:
- Criar um ativo;
- Atualizar detalhes de um ativo;
- Ver detalhes de um ativo;
- Listar ativos;
- Excluir um ativo.

#### Cada registro de ativo deve conter os seguintes campos:

- id (gerado automaticamente);
- model (ex.: Dell XPS 13);
- manufacturer (ex.: Dell, HP, Lenovo);
- category (ex.: Laptop, Servidor, Impressora);
- notes (campo de texto livre para adicionar observações relevantes).

### Frontend

Desenvolver uma interface web que permita ao usuário interagir com a API e realizar as ações
diponíveis.

#### A interface web deve permitir o usuário realizar as seguintes ações:

- Cadastrar um novo ativo;
- Listar todos os ativos cadastrados;
- Visualizar os detalhes de um ativo específico;
- Editar e excluir um ativo.

**Nota**: Não é necessário desenvolver uma tela de login para este desafio. O foco principal é a
implementação das funcionalidades de gestão de ativos, portanto, o usuário deverá acessar
diretamente o sistema sem precisar de autenticação.


## Requisitos do Projeto
- Escolha livremente as tecnologias para desenvolver tanto o backend quanto o frontend;
- Certifique-se de que variáveis, código e strings estejam todos em inglês;
- Inclua a documentação do projeto com:
    - Uma breve descrição;
    - Instruções de instalação (setup) e testes;
    - Se você fornecer uma configuração Docker, certifique-se de que também funcione sem Docker;
    - Uma breve descrição do ambiente usado para rodar o projeto (computador, SO, editor de
    texto/IDE, bibliotecas, etc.).

## Recomendações
- Escreva testes;
- Siga as melhores práticas de programação;
- Use as melhores práticas de git com mensagens de commit claras;
- Seja cuidadoso ao modelar o banco de dados;
- Valorizamos a simplicidade, então configure seu projeto de forma a facilitar nossa avaliação.


Se algo não estiver claro, entre em contato conosco.
