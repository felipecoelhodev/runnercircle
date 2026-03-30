# Runner Circle

O **Runner Circle** é uma plataforma social dedicada a corredores e entusiastas de atividades físicas. Nela, os usuários podem registrar seus treinos, compartilhar estatísticas de performance, acompanhar o progresso da comunidade e gerenciar seu perfil esportivo.

## Tecnologias Utilizadas

- **React**: Biblioteca principal para a interface do usuário.
- **GraphQL / Apollo Client / REST**: Para consumo de dados e gerenciamento de estado de rede.
- **Tailwind CSS**: Estilização moderna e responsiva.
- **Material UI Icons**: Conjunto de ícones para navegação.
- **JSON Server (Mock)**: Simulação de API REST para autenticação e dados de perfil.

## Funcionalidades

- **Feed de Atividades**: Visualize os treinos da comunidade com filtros por categoria (Corrida/Caminhada).
- **Registro de Treinos**: Formulário completo para salvar tempo, distância, ritmo, calorias, elevação e BPM.
- **Perfil do Usuário**: Edição de informações pessoais, bio e localização.
- **Autenticação**: Fluxo de Login e Criação de Conta.
- **Design Responsivo**: Layout adaptado para Desktop (Sidebar) e Mobile (Bottom Navigation).

## Como Executar o Projeto

**Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/react-runner-circle.git
 ```
Instale as dependências:
 ```bash
npm install
 ```
Inicialização dos servidores (1 servidor GraphQL e 1 servidor REST) :

Abra um terminal e inicialize o servidor GraphQL:
 ```bash
npm run server:json-graphql
 ```
Abra outro terminal e inicialize o servidor REST:
```bash
npm run server:json-server
```
Por fim abra um terceiro terminal e inicie a aplicação React:
 ```bash
npm run dev
```

## Estrutura de Dados (GraphQL)
A aplicação utiliza as seguintes operações principais:

GET_FEED: Recupera todas as postagens.

GET_FEED_BY_CATEGORY: Filtra atividades por tipo.

ADD_FEED_POST: Cria uma nova atividade no feed.

DELETE_FEED_POST: Remove uma postagem existente.
