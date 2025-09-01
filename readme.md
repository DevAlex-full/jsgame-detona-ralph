# 🎮 Detona Ralph - Jogo de Reflexos

Um jogo inspirado no clássico "Whac-a-Mole" com temática do personagem Ralph do filme da Disney. O objetivo é clicar no Ralph sempre que ele aparecer em uma das janelas, acumulando pontos antes que o tempo acabe.

## 🎯 Sobre o Projeto

Este é um jogo web desenvolvido em HTML5, CSS3 e JavaScript puro, onde o jogador deve ter reflexos rápidos para clicar no Ralph que aparece aleatoriamente em uma grade 3x3. O jogo apresenta:

- **Mecânica simples e viciante**: Clique no Ralph para marcar pontos
- **Sistema de tempo**: 60 segundos de duração
- **Pontuação dinâmica**: Acompanhe sua performance em tempo real
- **Feedback sonoro**: Som de acerto para maior imersão
- **Design retrô**: Estética inspirada em jogos clássicos de fliperama

## 🚀 Funcionalidades

### ⭐ Principais Features
- **Grid 3x3 interativo**: 9 quadrados onde o Ralph pode aparecer
- **Cronômetro regressivo**: 60 segundos de gameplay
- **Sistema de pontuação**: Contador de acertos em tempo real
- **Aparição aleatória**: O Ralph surge em posições imprevisíveis
- **Feedback audiovisual**: Som de acerto e animações visuais
- **Interface responsiva**: Compatível com diferentes tamanhos de tela

### 🎨 Elementos Visuais
- Fonte pixelizada "Press Start 2P" para nostalgia retrô
- Background temático com textura de parede
- Cores vibrantes e contrastantes para melhor visibilidade
- Sprite do Ralph como elemento principal do jogo

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e moderna
- **CSS3**: Estilização responsiva e animações
- **JavaScript ES6+**: Lógica do jogo e interatividade
- **Web Audio API**: Efeitos sonoros
- **Google Fonts**: Tipografia customizada

## 📁 Estrutura do Projeto

```
detona-ralph/
├── index.html              # Arquivo principal HTML
├── src/
│   ├── styles/
│   │   ├── reset.css       # Reset de estilos padrão
│   │   └── main.css        # Estilos principais
│   ├── scripts/
│   │   └── engine.js       # Lógica principal do jogo
│   ├── imagens/
│   │   ├── player.png      # Sprite do jogador
│   │   ├── ralph.png       # Sprite do Ralph
│   │   └── wall.png        # Textura de fundo
│   └── audios/
│       └── hit.m4a         # Som de acerto
└── README.md
```

## 🎮 Como Jogar

1. **Início**: O jogo inicia automaticamente ao carregar a página
2. **Objetivo**: Clique no Ralph sempre que ele aparecer nos quadrados
3. **Pontuação**: Cada clique certeiro soma 1 ponto
4. **Tempo**: Você tem 60 segundos para fazer o máximo de pontos
5. **Fim de jogo**: Ao final, sua pontuação total será exibida

### 🎯 Dicas para Alta Pontuação
- Mantenha o foco na grade inteira
- Desenvolva reflexos rápidos
- Clique assim que o Ralph aparecer
- Evite cliques desnecessários em quadrados vazios

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Não requer instalação de dependências

### Instalação
1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` no seu navegador
3. O jogo iniciará automaticamente

```bash
# Clonando o repositório
git clone [URL-DO-REPOSITORIO]
cd detona-ralph

# Executando localmente
# Simplesmente abra index.html no navegador
# ou use um servidor local:
python -m http.server 8000
# Acesse: http://localhost:8000
```

## 🎨 Características Técnicas

### Performance
- **FPS**: 60fps para animações suaves
- **Responsividade**: Adaptável a diferentes resoluções
- **Compatibilidade**: Suporte a navegadores modernos
- **Otimização**: Código limpo e performático

### Arquitetura do Código
- **Padrão State Management**: Gerenciamento centralizado do estado
- **Event-Driven**: Sistema baseado em eventos
- **Modular**: Funções bem definidas e reutilizáveis
- **Clean Code**: Código legível e bem documentado

## 🌟 Melhorias Futuras

- [ ] Sistema de vidas/chances
- [ ] Níveis de dificuldade progressiva
- [ ] Ranking local de melhores pontuações
- [ ] Modo multiplayer
- [ ] Power-ups especiais
- [ ] Animações mais elaboradas
- [ ] Versão mobile otimizada
- [ ] Integração com redes sociais

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abrir um Pull Request
