# 🎲 RPG in a Tab

**RPG in a Tab** é um projeto de RPG de mesa online desenvolvido em Flutter, focado em trazer uma experiência simples, interativa e acessível para jogadores e mestres de RPG. O projeto está em fase inicial de desenvolvimento e conta com o auxílio do ChatGPT.

## 🚀 Sobre o Projeto

RPG in a Tab permite criar e gerenciar partidas de RPG diretamente no navegador. A ideia é ter um ambiente leve e intuitivo, permitindo que jogadores e mestres interajam em tempo real com facilidade.

## ⚙️ Funcionalidades Atuais

### Jogadores
- **Criação e Edição de Personagens**:
  - Escolha nome, raça, classe e distribua pontos entre atributos.
  - Limite inicial de até **3 personagens** por usuário (com possibilidade futura de expansão via compra).
- **Visualização do Perfil**:
  - Estatísticas como partidas jogadas, salas criadas e partidas mestradas.

### Mestre
- **Criação de salas**:
  - Gere um código para jogadores entrarem em sua sala.
- **Controle de Narrativa**:
  - Interface própria para o mestre narrar e disponibilizar escolhas aos jogadores.

## 🎯 Mecânicas do Jogo

### Criação de Personagem
- **Atributos Iniciais**: Cada personagem começa com 5 pontos livres para distribuir além de 1 ponto obrigatório em cada atributo.
- **Atributos Disponíveis**:
  - Ataque Físico
  - Ataque Mágico
  - Defesa Física
  - Defesa Mágica
  - Velocidade

### Sistema de Combate Simplificado
- Cada jogador realiza uma rolagem de dado:
  - **Sucesso**: O inimigo recebe dano.
  - **Falha**: O jogador recebe dano.
  - **2 ou mais sucessos**: Inimigo derrotado automaticamente.
- O mestre rola um dado para definir o dano causado pelos inimigos.

### Sistema de Progressão
- Personagens ganham 1 ponto por batalha vencida para distribuir em atributos.
- Cada ponto em "Vida" equivale a +10 pontos no total do atributo.

## 🛠️ Tecnologias Utilizadas
- **Flutter (Web)** para o frontend.
- **Firebase** para autenticação e sincronização em tempo real.
- **Firestore** como banco de dados.

## 📌 Roadmap Futuro
- Venda de slots adicionais para criação de personagens.
- Sistema Premium com funcionalidades extras.
- Implementação de sistema avançado de combate.
- Gamificação e sistema de conquistas.

## 🧠 Apoio
Este projeto está sendo desenvolvido com o auxílio do **ChatGPT**, uma ferramenta de Inteligência Artificial da OpenAI.

## 📜 Licença
Este projeto é open-source e está sob a licença MIT.
