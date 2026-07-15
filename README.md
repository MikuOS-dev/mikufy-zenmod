# Mikufy — Zen Mod 🎵

Um mod completo para o Zen Browser inspirado em Hatsune Miku, com tema visual na UI, boosts para sites específicos, animações e efeitos glow/blur.

## 🎨 Funcionalidades

### Tema Completo na UI
- **Sidebar & Tabs**: Visual Miku com cores turquoise (`#39C5BB`) e rosa (`#E83F6F`)
- **URL Bar**: Background semi-transparent com blur e glow no foco
- **Toolbar**: Botões de navegação com acentos na cor primária
- **Menus & Popups**: Glass morphism escuro com blur
- **Scrollbar**: Estilo personalizado (thin ou hidden)
- **Selection**: Cor de seleção turquoise
- **Workspaces**: Indicador com glow animado

### Boosts para Sites (16 sites)
Google, YouTube, Twitter/X, GitHub, Discord, Reddit, TikTok, Twitch, Spotify, Wikipedia, WhatsApp, LinkedIn, ChatGPT e nova aba padrão do Firefox.

### Animações
- Glow pulsante no indicador de workspace
- Fade-in suave nos menus
- Slide-in nas popups
- Scale animado na seleção de tabs
- Transições suaves em hover/click

### Efeitos Glow/Blur
- Glow na sidebar e tabs ativos
- Glow na URL bar ao focar
- Backdrop blur em menus, toolbar e sidebar
- Efeitos de glass morphism

### Preferências Configuráveis
| Preferência | Tipo | Padrão | Descrição |
|---|---|---|---|
| `mikufy.glow` | boolean | `true` | Ativar efeito glow |
| `mikufy.blur` | boolean | `true` | Ativar backdrop blur |
| `mikufy.animations` | boolean | `true` | Ativar animações |
| `mikufy.sidebar-transparency` | boolean | `true` | Sidebar transparente |
| `mikufy.tab-hover-glow` | boolean | `false` | Glow nos tabs ao hover |
| `mikufy.urlbar-glow` | boolean | `true` | Glow na URL bar ao focar |
| `mikufy.color-primary` | string | `#39C5BB` | Cor primária |
| `mikufy.color-secondary` | string | `#E83F6F` | Cor secundária |
| `mikufy.scrollbar-style` | enum | `thin` | Estilo da scrollbar |
| `mikufy.compact-tabs` | boolean | `false` | Tabs compactas |

## 📦 Instalação

1. Abra o Zen Browser
2. Vá em `about:config`
3. Habilite `zen.mods.enabled`
4. Vá em **Settings → Mods**
5. Clique em **Load Mod** e selecione esta pasta
6. Reinicie o browser

## 🏗️ Estrutura

```
Mikufy-ZenMod/
├── userChrome.css    # Tema da UI do browser (sidebar, tabs, URL bar, menus...)
├── userContent.css   # Boosts para sites específicos (Google, YouTube, GitHub...)
├── preferences.json  # Opções configuráveis no painel de mods
└── README.md         # Esta documentação
```

## 🎯 Compatibilidade

- **Browser**: Zen Browser (todas as versões recentes)
- **Tema**: Funciona com tema escuro do Zen
- **Plataforma**: Windows, macOS, Linux

## ⚙️ Personalização

As preferências podem ser ajustadas em **Settings → Mods → Mikufy**. Cada toggle e opção tem efeito imediato na UI do browser.

Para mudar as cores primárias, edite as variáveis CSS no topo do `userChrome.css` e `userContent.css`.

## 📝 Licença

MIT — Livre para uso e modificação.
