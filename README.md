Organizador de Tarefas

# Projeto de Gerenciamento de Tarefas e Projetos

Este projeto é um sistema de gerenciamento de tarefas e projetos, desenvolvido em HTML, CSS, e JavaScript. A interface é construída para exibir tarefas e projetos organizados, com funcionalidades como cards personalizáveis, opções de configuração, e suporte para sub-tarefas.

## Tecnologias Utilizadas
- **IDE**: VS Code / Studio
- **Front-end**: HTML, CSS, Python
- **Python**:

### Equipe de Desenvolvimento
- **Back-end**: Adriel, Helder
- **Front-end**: Ewerton, Geonobri, Fábio
- **API**: Ewerton

---

## Especificações do Projeto

### Cores do Projeto
- **Paleta**: Branco, Azul, Roxo, Preto
- **Fonte**: Sanz Serif
- oBS.: Preferência por letras em preto

### Tela de Login
- Campos: **E-mail** e **Senha**
- Funcionalidades adicionais:
  - Opção de "Esqueceu a senha"
  - Botão de "Cadastrar"
  - Login com conta de terceiros

---

### Tela Principal

#### Exibição de Tarefas e Projetos
- Listagem de **Projetos** e **Tarefas** por nome
- Ícones opcionais nos projetos
- Tarefas incluem opções de:
  - Marcar como **Concluído**
  - Agendamento com **Calendário**

#### Cards Personalizáveis
- Personalização de:
  - **Cor**
  - **Título** e **Subtítulo**
- Funcionalidades:
  - Listas com **Checkbox** e **Radio buttons**
  - Opção de arrastar e soltar para organização no **Modo Quadro**

#### Menu Lateral de Configurações
- Acesso às opções de:
  - **Perfil**
  - **Configurações**
  - **Criar Card**
  - **Consultar Cards**
  - Criar **Projetos** com funções

#### Funções Dentro do Card
- Configurações de **Prioridade**
- Definição de **Data de Conclusão**
- **Título** e **Subtítulo**
- Adição de **Comentários**
- Criação de **Subtarefas**:
  - Marcar como concluída
  - Adicionar comentários nas subtarefas

#### Parte Superior da Tela
- Botões para:
  - Adicionar novo **Card**
  - Acessar ícone de **Configuração**

#### Menu Central
- Menu abre centralizado na tela para acesso facilitado

---

### Seções Adicionais

#### Perfil
- Exibe informações:
  - **Foto**
  - **E-mail**
  - **Dados de Endereço**
  - **Dados Pessoais** (não obrigatórios)

#### Criar Card
- Mesmas funcionalidades dos cards na tela principal

#### Consulta de Cards
- Exibe:
  - Cards **Concluídos**
  - Cards **Em andamento**
  - Opção de **Edição**

#### Configurações
- **Configuração de Tema**
- **Termo de Privacidade**
- **Número da Versão**

---

## Fluxo de Trabalho e Controle de Versão

### Git e Colaboração
- Projeto hospedado no **GitHub**, com acesso compartilhado
- Principais comandos:
  - **Commit**: Para atualizar o código no repositório
  - **Pull**: Para atualizar o código local

### Boas Práticas de Branching
- Trabalhar sempre no branch **develop**
  - **Não** fazer alterações diretamente no branch **master**
- Para funções específicas, utilizar um branch de **feature**
  - Validar a função e atualizar os repositórios de **develop** e **master** após aprovação

---

Este projeto segue um fluxo de desenvolvimento colaborativo. Qualquer dúvida sobre o código ou contribuições pode ser discutida com a equipe.



## Instruções para Clonar o Repositório e Inicializar o Git

1. **Clone o repositório**:
   ```bash
   git clone git@github.com:usuario/organizador.git
- **INICIALIZAR O GITHUB**   git init

- **ADICIONAR CÓDIGO**   git add.

- **DAR VERSÃO**   git commit -m "versao que quer"

- **CONSULTAR ULTIMA VERSÃO**   git logs

- ** ATUALIZAR COMMIT**   git push origin main
