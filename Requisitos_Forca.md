# 📌 Requisitos do Jogo de Forca Online

## 📌 1. Requisitos Funcionais

### 🎮 Mecanismos de Jogo
- O jogo deve demonstrar um tutorial em vídeo explicando as regras na primeira vez que o jogador abrir o jogo, com a opção de pular.
- O jogo deve permitir partidas multiplayer de até dois jogadores conectados simultaneamente.
- O jogo deve parear dois jogadores disponíveis com base no nível de experiência ou de forma aleatória.
- O jogo deve exibir corretamente as jogadas realizadas por ambos os jogadores.
- O jogo deve gerar um ID único para cada jogador ao se conectar, garantindo a identificação correta da sessão.
- O jogo deve finalizar a partida assim que um dos jogadores vencer e exibir a palavra correta.
- O jogo deve determinar o vencedor corretamente com base nas regras estabelecidas.
- O jogo deve estabelecer um tempo limite para cada rodada (exemplo: 60 segundos por turno).
- O jogo deve selecionar palavras aleatórias de um banco de dados adequado ao idioma escolhido.
- O jogo deve permitir que cada jogador solicite até 3 dicas por partida.

### 🎨 Interface e Experiência do Usuário
- O jogo deve permitir que os jogadores escolham um nome ou avatar personalizado.
- O jogo deve destacar as letras já utilizadas e indicar visualmente as tentativas restantes.
- O jogo deve exibir mensagens quando um jogador tentar repetir uma letra já usada.

### 🌍 Recursos Online e Comunicação
- O jogo deve permitir que os jogadores enviem emojis ou mensagens rápidas para interação durante a partida.
- O jogo deve exibir as jogadas do adversário em tempo real com um atraso máximo de 500ms, garantindo uma experiência fluida.
- O jogo deve parear dois jogadores em no máximo 2 minutos; caso não haja oponente disponível, o jogador poderá optar por jogar contra um bot.
- O jogo deve oferecer um modo offline contra bots para treinamento, com níveis de dificuldade ajustáveis.
- O jogo deve permitir a reconexão do jogador em caso de perda de conexão dentro de um tempo limite sem que a partida seja perdida.

---

## 📌 2. Requisitos Não Funcionais

### 🚀 Performance e Disponibilidade
- O jogo deve responder às ações do jogador em menos de 500ms.
- O sistema deve suportar até 2 jogadores simultâneos sem comprometer a jogabilidade.
- O jogo deve carregar completamente em menos de 2 segundos.

### 🔒 Segurança e Dados
- O jogo deve impedir que um jogador modifique a palavra oculta no cliente para evitar trapaças.
- Nenhuma informação sensível do jogador deve ser armazenada ou compartilhada sem consentimento.
- O jogo deve garantir conexões seguras entre os jogadores para evitar manipulações externas.

Gabriel Nascimento
Turma 13 - Engenharia de Software

