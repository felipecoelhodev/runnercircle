# 🏃‍♂️ Runner Circle

O **Runner Circle** é uma plataforma social dedicada a corredores e entusiastas de atividades físicas. Nela, os usuários podem registrar seus treinos, compartilhar estatísticas de performance, acompanhar o progresso da comunidade e gerenciar seu perfil esportivo.

## 🚀 Tecnologias Utilizadas

- **React**: Biblioteca principal para a interface do usuário.
- **GraphQL / Apollo Client**: Para consumo de dados e gerenciamento de estado de rede.
- **Tailwind CSS**: Estilização moderna e responsiva.
- **Material UI Icons**: Conjunto de ícones para navegação.
- **JSON Server (Mock)**: Simulação de API REST para autenticação e dados de perfil.

## ✨ Funcionalidades

- **Feed de Atividades**: Visualize os treinos da comunidade com filtros por categoria (Corrida/Caminhada).
- **Registro de Treinos**: Formulário completo para salvar tempo, distância, ritmo, calorias, elevação e BPM.
- **Perfil do Usuário**: Edição de informações pessoais, bio e localização.
- **Autenticação**: Fluxo de Login e Criação de Conta.
- **Design Responsivo**: Layout adaptado para Desktop (Sidebar) e Mobile (Bottom Navigation).

## 🛠️ Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/react-runner-circle.git](https://github.com/seu-usuario/react-runner-circle.git)
   Instale as dependências:
   ```

Bash
npm install
Inicie o servidor de Mock (JSON Server):
(Certifique-se de ter o json-server instalado ou use o comando configurado no seu package.json)

Bash
npx json-server --watch db.json --port 3002
Inicie a aplicação React:

Bash
npm start
📊 Estrutura de Dados (GraphQL)
A aplicação utiliza as seguintes operações principais:

GET_FEED: Recupera todas as postagens.

GET_FEED_BY_CATEGORY: Filtra atividades por tipo.

ADD_FEED_POST: Cria uma nova atividade no feed.

DELETE_FEED_POST: Remove uma postagem existente.

---

## Sugestão de "About" (Descrição Curta)

**PT-BR:**

> 👟 Uma rede social para corredores focada em performance e comunidade. Desenvolvida com React, GraphQL e Tailwind CSS como parte do currículo Alura. Permite registrar treinos, filtrar atividades por categoria e gerenciar perfis de atletas.

**EN:**

> 👟 A social network for runners focused on performance and community. Built with React, GraphQL, and Tailwind CSS. Features workout logging, activity filtering, and profile management.

---
