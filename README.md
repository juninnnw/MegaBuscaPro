# ⚡ MEGA BUSCA PRO v3.0

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-lightgrey.svg)

**Sistema Avançado de Busca Multi-Fonte com Interface Gráfica Profissional**

[Características](#-características) • [Instalação](#-instalação) • [Como Usar](#-como-usar) • [Fontes](#-fontes-disponíveis) • [FAQ](#-faq)

</div>

---

## 📋 Índice

- [Sobre](#-sobre)
- [Características](#-características)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Como Usar](#-como-usar)
  - [Busca Geral](#1-busca-geral)
  - [Busca de Filmes](#2-busca-de-filmes)
  - [Busca de Séries](#3-busca-de-séries)
  - [Busca de Episódios](#4-busca-de-episódios-completos)
  - [Busca no Telegram](#5-busca-no-telegram)
  - [Busca de Grupos WhatsApp](#6-busca-de-grupos-whatsapp)
- [Fontes Disponíveis](#-fontes-disponíveis)
- [Sistema de Relevância](#-sistema-de-relevância)
- [Configuração Avançada](#-configuração-avançada)
- [Criar Executável](#-criar-executável)
- [Avisos Legais](#-avisos-legais)
- [FAQ](#-faq)
- [Contribuindo](#-contribuindo)
- [Licença](#-licença)

---

## 🎯 Sobre

**MEGA BUSCA PRO** é uma ferramenta profissional de busca que consulta **60+ fontes** simultaneamente, incluindo APIs oficiais, sites de torrents, plataformas de streaming, redes sociais e muito mais. 

Com sistema inteligente de relevância, interface moderna e resultados organizados por score de qualidade, é a solução definitiva para buscas abrangentes na internet.

### ✨ Destaques v3.0

- 🎯 **Sistema de Relevância Inteligente** (0-100%)
- 📋 **Busca Completa de Episódios** de séries (S01E01 até S10E99)
- 💬 **Busca de Grupos WhatsApp** (5 fontes especializadas)
- 🏴‍☠️ **30+ Sites de Torrents** com mirrors
- 📐 **Interface Compacta** (900x700) e profissional
- 💾 **Export Automático** de resultados
- 🔍 **Filtros Avançados** personalizáveis

---

## 🚀 Características

### 🌐 Busca Multi-Fonte

| Categoria | Fontes | Descrição |
|-----------|--------|-----------|
| **APIs Legais** | 8 | GitHub, Reddit, StackOverflow, YouTube, Google Drive |
| **Torrents** | 30+ | 1337x, TPB, RARBG, Zooqle, Kickass, etc. |
| **Filmes** | 12 | YTS, FMovies, Putlocker, etc. |
| **Séries** | 10 | EZTV, ShowRSS, WatchSeries, etc. |
| **Telegram** | 8 | TGStat, Telemetr, TGChannels, etc. |
| **WhatsApp** | 5 | GrupoZap, Grupos Whats, busca Google |

### 🎯 Sistema de Relevância

Cada resultado recebe um **score de 0 a 100%** baseado em:

- ✅ Presença da query no URL
- ✅ Keywords relevantes da categoria
- ✅ Qualidade (1080p, 720p, BluRay)
- ✅ Seeds/Peers (torrents)
- ✅ Domínios confiáveis
- ✅ Popularidade (upvotes, views)

### 🎨 Interface Profissional

- 🌙 **Tema Escuro** moderno e confortável
- 📊 **7 Abas Especializadas** por tipo de busca
- 📈 **Stats em Tempo Real** (progresso, quantidade, média)
- 🎛️ **Filtros Ajustáveis** de relevância mínima
- 💾 **Export Automático** para .txt
- 📋 **Clipboard Support** (copiar resultados)
- 🔗 **Duplo Clique** para abrir links

---

## 📦 Pré-requisitos

- **Python 3.8+** instalado
- **Conexão com internet** estável
- **Sistema Operacional:** Windows, Linux ou macOS

### Bibliotecas Necessárias

```bash
aiohttp          # Requisições assíncronas
python-dotenv    # Variáveis de ambiente
tkinter          # Interface gráfica (incluído no Python)
```

---

## 💻 Instalação

### Método 1: Clone do Repositório

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/mega-busca-pro.git
cd mega-busca-pro

# Instale as dependências
pip install -r requirements.txt

# Execute o programa
python mega_busca_pro.py
```

### Método 2: Download Direto

1. Baixe o arquivo `mega_busca_pro.py`
2. Instale as dependências:
   ```bash
   pip install aiohttp python-dotenv
   ```
3. Execute:
   ```bash
   python mega_busca_pro.py
   ```

### Método 3: Executável (Windows)

1. Baixe `MegaBuscaPro.exe` da [página de releases](https://github.com/seu-usuario/mega-busca-pro/releases)
2. Execute diretamente (não precisa Python instalado)

---

## 📖 Como Usar

### Iniciando o Programa

```bash
python mega_busca_pro.py
```

A interface gráfica será aberta automaticamente.

---

### 1. 🌐 Busca Geral

**Para:** Buscar em GitHub, Reddit, YouTube, Google Drive e torrents gerais.

#### Passo a Passo:

1. **Selecione a aba:** `🌐 Geral`
2. **Escolha as fontes:** Marque/desmarque as checkboxes
3. **Digite a busca:** Ex: `python machine learning`
4. **Clique em:** `🔍 BUSCAR`
5. **Aguarde:** O console mostrará o progresso
6. **Veja os resultados:** Aba `📊 Resultados` abrirá automaticamente

#### Fontes Incluídas:

- ✅ GitHub Code & Repositories
- ✅ Reddit Discussions
- ✅ YouTube Videos
- ✅ Google Drive Files
- 🏴‍☠️ 30+ sites de torrents

#### Exemplo:

```
Busca: "react tutorial"
Resultado: Repositórios GitHub, vídeos YouTube, discussões Reddit
```

---

### 2. 🎬 Busca de Filmes

**Para:** Encontrar filmes em alta qualidade (HD, BluRay, 1080p).

#### Passo a Passo:

1. **Selecione a aba:** `🎬 Filmes`
2. **Digite o nome do filme:** Ex: `Inception 2010`
3. **Fontes recomendadas:**
   - ✅ YTS (melhor qualidade)
   - ✅ 1337x (mais completo)
   - ✅ RARBG (bons seeds)
4. **Clique em:** `🔍 BUSCAR`

#### Recursos Especiais:

- 🎯 **Prioriza HD:** 1080p e 720p têm score maior
- 📊 **Filtra por Seeds:** Mais seeds = maior relevância
- 🎬 **YTS API:** Acesso direto a torrents de qualidade

#### Exemplo:

```
Busca: "The Matrix 1999"
Resultado: Torrents 1080p, links de streaming, magnets
```

#### Dicas:

- Use o **nome original** do filme em inglês
- Adicione o **ano** para maior precisão
- Prefira **YTS** para filmes em alta qualidade

---

### 3. 📺 Busca de Séries

**Para:** Encontrar temporadas completas de séries.

#### Passo a Passo:

1. **Selecione a aba:** `📺 Séries`
2. **Digite o nome da série:** Ex: `Breaking Bad`
3. **Fontes recomendadas:**
   - ✅ EZTV (especializado em séries)
   - ✅ 1337x (mais variedade)
4. **Clique em:** `🔍 BUSCAR`

#### Recursos Especiais:

- 📦 **Busca Packs:** Temporadas completas
- 🎯 **EZTV API:** Acesso direto a episódios
- 📊 **Score por Qualidade:** Prioriza HD e alto seeds

#### Exemplo:

```
Busca: "Game of Thrones"
Resultado: Temporadas completas, packs, episódios individuais
```

---

### 4. 📋 Busca de Episódios Completos

**⭐ RECURSO EXCLUSIVO v3.0**

**Para:** Listar TODOS os episódios disponíveis de uma série (S01E01 até S10E99).

#### Passo a Passo:

1. **Selecione a aba:** `📋 Episódios`
2. **Digite o nome da série:** Ex: `Friends`
3. **Clique em:** `📋 LISTAR TODOS OS EPISÓDIOS`
4. **Aguarde:** A busca procura em 10 temporadas
5. **Resultado:** Lista completa organizada por temporada

#### O que você verá:

```
━━━ TEMPORADA 01 ━━━

  S01E01 [85%] EZTV     magnet:?xt=urn:btih:...
  S01E02 [90%] EZTV     magnet:?xt=urn:btih:...
  S01E03 [78%] 1337x    https://1337x.to/...
  ...

━━━ TEMPORADA 02 ━━━

  S02E01 [92%] EZTV     magnet:?xt=urn:btih:...
  ...
```

#### Recursos:

- 📊 **Score por Episódio:** Veja a qualidade
- 🔗 **Links Diretos:** Duplo clique para abrir
- 📁 **Organizado:** Por temporada e episódio
- 🎯 **Até 10 Temporadas:** Busca automática

#### Dicas:

- Funciona melhor com **séries populares**
- Use o **nome original** em inglês
- A busca pode demorar **2-3 minutos** (busca 10 temporadas)

---

### 5. ✈️ Busca no Telegram

**Para:** Encontrar canais e grupos públicos do Telegram.

#### Passo a Passo:

1. **Selecione a aba:** `✈️ Telegram`
2. **Digite palavras-chave:** Ex: `cursos python`
3. **Clique em:** `🔍 BUSCAR`

#### Fontes Incluídas:

- TGStat (melhor buscador)
- Telemetr
- TGChannels
- Telegram DB
- Lyzem
- XTEA
- Sssoou
- TGFinder

#### Exemplos de Busca:

| Busca | Resultado |
|-------|-----------|
| `filmes` | Canais de filmes e séries |
| `ebooks` | Canais de livros digitais |
| `cursos` | Canais educacionais |
| `música` | Canais de música |
| `notícias` | Canais de notícias |

#### Dicas:

- Use **português** ou **inglês**
- Seja **específico:** "cursos python" é melhor que "cursos"
- Explore **canais relacionados** nos resultados

---

### 6. 💬 Busca de Grupos WhatsApp

**⭐ RECURSO NOVO v3.0**

**Para:** Encontrar links de convite de grupos públicos do WhatsApp.

#### Passo a Passo:

1. **Selecione a aba:** `💬 WhatsApp`
2. **Digite o tema:** Ex: `programação python`
3. **Clique em:** `🔍 BUSCAR`

#### Fontes Incluídas:

- Google (site:chat.whatsapp.com)
- Bing (buscas especializadas)
- GrupoZap.com.br
- GruposWhats.app
- Busca de convites públicos

#### Exemplos de Busca:

| Busca | Resultado |
|-------|-----------|
| `freelas` | Grupos de freelancers |
| `vendas` | Grupos de vendas |
| `futebol` | Grupos de esportes |
| `receitas` | Grupos de culinária |
| `concursos` | Grupos de estudos |

#### ⚠️ IMPORTANTE:

- ✅ **Verifique** a descrição antes de entrar
- ✅ **Cuidado** com grupos suspeitos
- ✅ **Não compartilhe** dados pessoais
- ❌ **Evite** grupos de vendas duvidosas

---

## 📊 Fontes Disponíveis

### ✅ APIs Legais (8 fontes)

| Fonte | Tipo | O que busca |
|-------|------|-------------|
| **GitHub** | Code/Repos | Código-fonte, repositórios, issues |
| **Reddit** | Discussions | Discussões, posts, subreddits |
| **StackOverflow** | Q&A | Perguntas e respostas técnicas |
| **YouTube** | Videos | Vídeos e tutoriais |
| **Google Drive** | Files | Arquivos públicos compartilhados |
| **Wayback Machine** | Archive | Páginas arquivadas |

### 🏴‍☠️ Torrents (30+ sites)

#### Principais:

- **1337x** (+ mirrors)
- **The Pirate Bay** (+ mirrors)
- **RARBG** (+ mirrors)
- **Torrentz2** (+ mirrors)
- **Zooqle**
- **Kickass Torrents** (+ mirrors)
- **TorrentGalaxy**
- **LimeTorrents**
- **Torlock**
- **MagnetDL**
- **RuTracker**
- **Nyaa** (anime)
- **SolidTorrents**
- **BTDigg**
- **BTDb**
- **ExtraTorrent**
- **Demonoid**
- **Idope**
- **TorrentDownloads**
- **TorrentFunk**

### 🎬 Filmes (12 sites)

- **YTS** (melhor qualidade)
- Popcorn Time
- FMovies
- Putlocker
- Movie4K
- GoMovies
- Vumoo
- PrimeWire
- SolarMovie
- LookMovie
- StreamLord

### 📺 Séries (10 sites)

- **EZTV** (especializado)
- ShowRSS
- TVSeries Online
- WatchSeries
- Series9
- ProjectFreeTV
- TVids
- SeriesHD
- WatchEpisodes

### ✈️ Telegram (8 buscadores)

- TGStat
- Telemetr
- TGChannels
- Telegram DB
- Lyzem
- XTEA
- Sssoou
- TGFinder

### 💬 WhatsApp (5 fontes)

- Google Search (site:chat.whatsapp.com)
- Bing Search
- GrupoZap.com.br
- GruposWhats.app
- Busca de convites

---

## 🎯 Sistema de Relevância

### Como Funciona

Cada resultado recebe um **score de 0.0 a 1.0** (exibido como 0-100%):

```python
Score = Base + Bônus de Query + Bônus de Keywords + Bônus de Domínio
```

### Critérios de Pontuação

| Critério | Pontuação | Exemplo |
|----------|-----------|---------|
| Query no URL | +50% | `python` em `github.com/learn-python` |
| Keywords relevantes | +10% cada | `1080p`, `bluray`, `magnet:` |
| Domínio confiável | +20% | github.com, yts.mx, reddit.com |
| Seeds altos (torrents) | até +15% | 1000+ seeds |
| Qualidade HD | +5% | 1080p, 720p |

### Filtro de Relevância

Na aba **📊 Resultados**, você pode filtrar por score mínimo:

- **0%** - Todos os resultados
- **30%** - Resultados relevantes (padrão)
- **50%** - Boa relevância
- **70%** - Alta relevância
- **90%** - Apenas excelentes

### Indicadores Visuais

- 🟢 **Verde** (70-100%): Excelente relevância
- 🟡 **Amarelo** (40-69%): Boa relevância
- 🔴 **Vermelho** (0-39%): Baixa relevância

---

## ⚙️ Configuração Avançada

### Tokens API (Opcional)

Para aumentar limites de requisições:

1. Clique em **🔑 Tokens** no rodapé
2. Configure:

#### GitHub Token

- Acesse: https://github.com/settings/tokens
- Generate new token (classic)
- Selecione: `public_repo`, `read:user`
- Cole no campo **GitHub Token**

**Benefícios:**
- 5000 requisições/hora (vs 60 sem token)
- Acesso a mais resultados

#### Bing API Key

- Acesse: https://www.microsoft.com/en-us/bing/apis/bing-web-search-api
- Crie uma conta gratuita
- Copie a API Key

**Benefícios:**
- Buscas mais precisas
- Resultados ranqueados

### Arquivo .env

Os tokens são salvos automaticamente em `.env`:

```env
GITHUB_TOKEN=ghp_xxxxxxxxxxxxxxxxxxxxx
BING_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxx
```

---

## 📦 Criar Executável

### Windows

```bash
# Instalar PyInstaller
pip install pyinstaller

# Criar executável
pyinstaller --onefile --windowed --name="MegaBuscaPro" --icon=icon.ico mega_busca_pro.py

# O executável estará em:
dist/MegaBuscaPro.exe
```

### Linux / macOS

```bash
pyinstaller --onefile --windowed --name="MegaBuscaPro" mega_busca_pro.py

# O executável estará em:
dist/MegaBuscaPro
```

### Opções Avançadas

```bash
# Com ícone customizado
pyinstaller --onefile --windowed --icon=icon.ico --name="MegaBusca" mega_busca_pro.py

# Sem console de debug
pyinstaller --onefile --noconsole --name="MegaBusca" mega_busca_pro.py

# Com arquivos adicionais
pyinstaller --onefile --add-data ".env:." mega_busca_pro.py
```

---

## ⚠️ Avisos Legais

### IMPORTANTE - LEIA COM ATENÇÃO

#### ⚖️ Responsabilidade

- ❌ **O desenvolvedor NÃO se responsabiliza** pelo uso do software
- ❌ **Você é 100% responsável** pelas suas ações
- ❌ **Não incentivamos atividades ilegais**

#### 🏴‍☠️ Torrents e Pirataria

- ⚠️ **Download de conteúdo protegido é ILEGAL** na maioria dos países
- ⚠️ **Use apenas para conteúdo legal** (open source, domínio público)
- ⚠️ **Respeite direitos autorais**
- ⚠️ **Use VPN** para proteger sua privacidade

#### 🌐 Darkweb e Fóruns

- ⚠️ **Conteúdo pode ser perigoso ou ilegal**
- ⚠️ **Use TOR Browser** obrigatoriamente
- ⚠️ **Cuidado com malware e scams**
- ⚠️ **Nunca forneça dados pessoais**

#### 💬 Grupos WhatsApp/Telegram

- ⚠️ **Verifique grupos** antes de entrar
- ⚠️ **Evite grupos suspeitos**
- ⚠️ **Não compartilhe informações sensíveis**

#### ✅ Uso Recomendado

Este software é ideal para:

- ✅ Pesquisa acadêmica e educacional
- ✅ Busca de conteúdo open source
- ✅ Encontrar recursos públicos legais
- ✅ Pesquisa de mercado
- ✅ Análise de dados públicos

---

## ❓ FAQ

### Perguntas Frequentes

#### 1. O programa é seguro?

✅ **Sim**, o código é open source e pode ser auditado. Não coleta dados pessoais nem instala malware.

#### 2. Preciso pagar?

✅ **Não**, o software é 100% gratuito e open source (licença MIT).

#### 3. Funciona sem internet?

❌ **Não**, é necessária conexão com internet para fazer as buscas.

#### 4. Por que alguns resultados não abrem?

Alguns sites podem estar:
- 🚫 Bloqueados no seu país
- 🚫 Fora do ar temporariamente
- 🚫 Requerendo VPN

**Solução:** Use uma VPN confiável.

#### 5. O programa demora muito?

⏱️ Depende:
- **Busca geral:** 10-30 segundos
- **Filmes/Séries:** 15-40 segundos
- **Episódios completos:** 2-3 minutos (busca 10 temporadas)

#### 6. Posso usar em dispositivos móveis?

❌ **Não diretamente**. É necessário Python e desktop. Mas você pode:
- Usar via **Remote Desktop**
- Rodar no **Termux** (Android, avançado)

#### 7. Os resultados são salvos?

✅ **Sim**, automaticamente em `results/` com timestamp.

#### 8. Como atualizar o programa?

```bash
git pull origin main
pip install -r requirements.txt --upgrade
```

#### 9. Encontrei um bug, o que faço?

Abra uma [issue no GitHub](https://github.com/seu-usuario/mega-busca-pro/issues) com:
- Descrição do problema
- Passos para reproduzir
- Sistema operacional
- Versão do Python

#### 10. Posso contribuir?

✅ **Sim!** Veja a seção [Contribuindo](#-contribuindo).

---

## 🤝 Contribuindo

Contribuições são muito bem-vindas! 

### Como Contribuir

1. **Fork** o repositório
2. **Clone** seu fork:
   ```bash
   git clone https://github.com/seu-usuario/mega-busca-pro.git
   ```
3. **Crie uma branch:**
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
4. **Faça suas alterações**
5. **Commit:**
   ```bash
   git commit -m "Adiciona nova funcionalidade X"
   ```
6. **Push:**
   ```bash
   git push origin feature/nova-funcionalidade
   ```
7. Abra um **Pull Request**

### Ideias para Contribuir

- 🔧 Adicionar novos sites/fontes
- 🐛 Corrigir bugs
- 🎨 Melhorar a interface
- 📝 Melhorar documentação
- 🌐 Traduzir para outros idiomas
- ⚡ Otimizar performance
- 🧪 Adicionar testes

### Código de Conduta

- ✅ Seja respeitoso
- ✅ Código limpo e documentado
- ✅ Teste antes de enviar
- ✅ Siga o estilo do projeto

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**.

```
MIT License

Copyright (c) 2025 juninnw

É concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia
deste software e arquivos de documentação associados (o "Software"), para lidar
com o Software sem restrição, incluindo, sem limitação, os direitos de usar,
copiar, modificar, fundir, publicar, distribuir, sublicenciar e/ou vender
cópias do Software...
```

Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🌟 Agradecimentos

- **Python** - Linguagem incrível
- **tkinter** - Interface gráfica
- **aiohttp** - Requisições assíncronas
- **Comunidade Open Source** - Por todas as ferramentas

---

## 📞 Contato

- **GitHub:** [@seu-usuario](https://github.com/seu-usuario)
- **Email:** seu.email@example.com
- **Issues:** [Reportar Bug](https://github.com/seu-usuario/mega-busca-pro/issues)

---

## 📊 Estatísticas

![GitHub stars](https://img.shields.io/github/stars/seu-usuario/mega-busca-pro)
![GitHub forks](https://img.shields.io/github/forks/seu-usuario/mega-busca-pro)
![GitHub issues](https://img.shields.io/github/issues/seu-usuario/mega-busca-pro)

---

<div align="center">

**⚡ MEGA BUSCA PRO v3.0**

Feito com ❤️ para a comunidade

[⬆️ Voltar ao topo](#-mega-busca-pro-v30)

</div>
