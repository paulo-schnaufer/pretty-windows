# pretty-windows 🪟✨

Guia completo para transformar o Windows 11 em uma experiência mais bonita, moderna e visualmente atraente, com efeitos de desfoque, translucidez e personalizações atuais.

## Índice

- [Informações Gerais](#informações-gerais)
- [Pré-requisitos](#pré-requisitos)
- [Instalação do Windhawk](#instalação-do-windhawk)
- [Configuração de Desfoque e Translucidez](#configuração-de-desfoque-e-translucidez)
- [Translucidez no Firefox (FlexFox)](#translucidez-no-firefox-flexfox)
- [Dicas Adicionais](#dicas-adicionais)
- [Solução de Problemas](#solução-de-problemas)
- [Recursos](#recursos)
## Informações Gerais

Este guia ajudará você a alcançar uma área de trabalho do Windows 11 bonita e moderna com:
- **Efeitos de desfoque** em janelas e elementos da interface
- **Planos de fundo translúcidos** para a barra de tarefas, janelas e menus
- **Firefox personalizado** com elementos translúcidos e usabilidade aprimorada
- **Melhorias visuais em todo o sistema** usando mods do Windhawk

## Pré-requisitos

Antes de começar, certifique-se de que você tem:
- Windows 11 (22H2 ou posterior recomendado)
- Acesso de administrador ao seu sistema
- Conexão com a internet para downloads
- Familiaridade básica com as Configurações do Windows

## Instalação do Windhawk

O Windhawk é uma plataforma poderosa de personalização que permite modificar o comportamento e a aparência do Windows usando mods criados pela comunidade.

### Passo 1: Baixar o Windhawk

1. Acesse o site oficial: [https://windhawk.net/](https://windhawk.net/)
2. Clique em **Download** para obter o instalador mais recente
3. Alternativamente, baixe diretamente do GitHub: [https://github.com/ramensoftware/windhawk/releases](https://github.com/ramensoftware/windhawk/releases)

### Passo 2: Instalar o Windhawk

1. Execute o instalador baixado (`windhawk_setup.exe`)
2. Siga o assistente de instalação:
   - Aceite o contrato de licença
   - Escolha o local de instalação (recomenda-se o padrão)
   - Clique em **Instalar**
3. Aguarde a conclusão da instalação
4. Inicie o Windhawk pelo menu Iniciar ou atalho na área de trabalho

### Passo 3: Configuração Inicial

1. Ao abrir o Windhawk, você verá a interface principal
2. Permita que o Windhawk seja executado como administrador quando solicitado
3. O Windhawk ficará na bandeja do sistema (ícone 🪝)

## Configuração de Desfoque e Translucidez

Transforme a interface do Windows com belos efeitos de desfoque e translucidez usando mods do Windhawk.

### Mods Essenciais

#### 1. **Translucent Windows**
Ativa efeitos de desfoque e translucidez nativos para o Windows 11.
1. Abra o Windhawk
2. Vá em **Explorar**
3. Pesquise por "Translucent Windows"
4. Clique em **Instalar**
5. Em **Configurações**, ajuste:
   - Rendering Customization:
     - Windows theme custom rendering: Ativar
     - Windows theme accent colorizer: Ativar
   - Effects: Blur (AccentBlurBehind)
   - AccentBlurBehind color blend: 8C000000 (preto translúcido)
   - Immersive darkmode titlebar: Ativar
   - Extend effects into entire windows: Ativar
6. Clique em **Salvar configurações**

#### 2. **Windows 11 Translucent Taskbar Styler**
Deixa a barra de tarefas translúcida com opacidade e desfoque personalizáveis.
1. Abra o Windhawk
2. Vá em **Explorar**
3. Pesquise por "Translucent Taskbar Styler"
4. Clique em **Instalar**
5. Em **Configurações**, ajuste:
   - **Theme**: TranslucentTaskbar
6. Clique em **Salvar configurações**

#### 3. **Windows 11 File Explorer Styler**
Adiciona efeitos de desfoque acrílico ao Explorador de Arquivos.
1. No Windhawk, pesquise por "Windows 11 File Explorer Styler"
2. Clique em **Instalar**
3. Em **Configurações**, ajuste:
   - **Theme**: Translucent Explorer11
4. Clique em **Salvar configurações**

#### 4. **Windows 11 Notification Center Styler**
Adiciona desfoque acrílico ao Centro de Notificações e outros menus.
1. Pesquise por "Windows 11 Notification Center Styler" nos mods do Windhawk
2. Clique em **Instalar**
3. Em **Configurações**, ajuste:
   - **Theme**: TranslucentShell
4. Clique em **Salvar configurações**

#### 5. **Windows 11 Start Menu Styler**
Personaliza o Menu Iniciar com efeitos de desfoque e translucidez.
1. Pesquise por "Windows 11 Start Menu Styler" no Windhawk
2. Clique em **Instalar**
3. Em **Configurações**, ajuste:
   - **Theme**: TranslucentStartMenu
4. Clique em **Salvar configurações**

## 🦊 Translucidez no Firefox (FlexFox)

Deixe o Firefox mais bonito com efeitos translúcidos e usabilidade aprimorada.

### Passo 1: Instalar o Firefox
1. Baixe o Firefox: [https://www.mozilla.org/firefox/](https://www.mozilla.org/firefox/)
2. Instale normalmente
3. Abra o Firefox

### Passo 2: Instalar o FlexFox
1. Instale [Sideberry](https://addons.mozilla.org/firefox/addon/sidebery/) (opcional, mas recomendado)
2. Baixe a versão apropriada do FlexFox:
   - [FlexFox](https://github.com/yuuqilin/FlexFox/archive/refs/heads/main.zip) para Firefox padrão
   - [FlexFox Beta](https://github.com/yuuqilin/FlexFox/archive/refs/heads/Beta.zip) para Firefox Beta/Nightly
   - [FlexFox ESR](https://github.com/yuuqilin/FlexFox/archive/refs/heads/ESR.zip) para Firefox ESR
3. No Firefox, acesse `about:support`, encontre a Pasta do Perfil e clique em "Abrir Pasta"
4. Copie a pasta `chrome` e o arquivo `user.js` do diretório scripts do FlexFox para a pasta do seu perfil do Firefox
5. Edite o `user.js` e remova os comentários (`//`) para ativar recursos adicionais, se desejar
   - Certifique-se de que:
      -  toolkit.legacyUserProfileCustomizations.stylesheets = true
      -  svg.context-properties.content.enabled = true
      -  sidebar.visibility = always-show
6. Reinicie o Firefox. Depois, exclua o `user.js` para que alterações futuras em `about:config` persistam
7. Configure o Sideberry:
   - Abra as configurações do Sideberry (ícone de engrenagem)
   - Limpe estilos existentes para evitar conflitos
   - Em Ajuda > Importar dados do complemento, importe `sidebery-settings.json` e `sidebery-styles.json` da pasta Sidebery do FlexFox
   - Se os estilos não funcionarem, tente importar novamente
8. Em `about:config`, pesquise por `uc.flex.` para alternar recursos do FlexFox

### Passo 3: Ativar suporte a Mica e papéis de parede personalizados
1. Em `about:config`, defina:
   - widget.windows.mica = true
   - widget.windows.mica.popups = 2
   - widget.windows.mica.toplevel-backdrop = 2
   - browser.tabs.allow_transparent_browser = true
   - uc.flex.browser-mica-transparency-level = 2
2. Deixe o tema do Firefox em automático. O Mica só funciona nesse modo (reinicie o Firefox após alterar)
   - Para detalhes: [🧊 Visual Background & Mica Effects](https://github.com/yuuqilin/FlexFox#-visual-background--mica-effects)
   - Se o fundo Mica ficar obstruído por janelas inativas, use Win + Home para minimizar todas as outras janelas

O efeito Mica é nativo. Para transparência em conteúdos web (ex: YouTube), use a extensão [Zen Internet](https://addons.mozilla.org/firefox/addon/zen-internet/).
Recomenda-se também instalar o [Dark Reader](https://addons.mozilla.org/firefox/addon/darkreader/).

### Passo 4: Deixe o VSCode translúcido (Opcional)
1. Instale a extensão [GlassIt-VSC](https://marketplace.visualstudio.com/items?itemName=auto-glass.glassit) no VSCode
2. Ajuste a opacidade com Ctrl+Alt+Z/Ctrl+Alt+C e alterne o efeito com Ctrl+Alt+X

## 💡 Dicas Adicionais

### Melhorias no Sistema

1. **Ative os efeitos de transparência do Windows**:
   - Configurações → Personalização → Cores
   - Ative **Efeitos de transparência**

2. **Use o modo escuro**:
   - Configurações → Personalização → Cores
   - Escolha o modo **Escuro** para melhor aparência dos efeitos

3. **Cor de destaque**:
   - Escolha uma cor de destaque que combine com os efeitos translúcidos
   - Ative **Mostrar cor de destaque em barras de título e bordas de janela**

4. **Papel de parede**:
   - Use wallpapers de alta qualidade e contraste médio
   - Evite fundos muito chamativos ou brilhantes
   - Gradientes funcionam muito bem com desfoque

### Otimização de desempenho

- **Desative efeitos na bateria**: No Windhawk, configure perfis de desempenho
- **Ajuste a qualidade do desfoque**: Reduza o raio do desfoque em hardware mais antigo
- **Monitore o uso da GPU**: Use o Gerenciador de Tarefas para garantir que os efeitos não estão causando lentidão

## 🔧 Solução de Problemas

### Windhawk

**Problema:** Mods não aplicam após instalação
- **Solução:** Reinicie o serviço do Windhawk ou o Windows
- Verifique se os mods estão ativados nas configurações do Windhawk
- Certifique-se de ter privilégios de administrador

**Problema:** Lentidão ou travamentos
- **Solução:** Desative alguns mods para identificar o causador
- Reduza a intensidade do desfoque nas configurações dos mods
- Atualize os drivers de vídeo

**Problema:** Windhawk não inicia
- **Solução:** Execute como administrador
- Verifique se o Windows Defender não bloqueou arquivos
- Reinstale o Windhawk do site oficial

### Firefox

**Problema:** userChrome.css não carrega
- **Solução:** Verifique se `toolkit.legacyUserProfileCustomizations.stylesheets` está como `true`
- O nome do arquivo deve ser exatamente `userChrome.css` (diferencia maiúsculas/minúsculas)
- O arquivo deve estar na pasta correta do perfil

**Problema:** Efeitos de desfoque não aparecem
- **Solução:** Atualize o Firefox para a versão mais recente (o suporte a blur pode variar)
- Windows 10/11 é necessário para suporte a backdrop-filter
- Tente aumentar os valores de opacidade no CSS

**Problema:** Elementos da interface invisíveis
- **Solução:** Aumente os valores de opacidade (ex: de 0.5 para 0.8)
- Ajuste as cores de fundo para menos transparência
- Adicione bordas aos elementos para melhor visibilidade

## 📚 Recursos

### Sites Oficiais
- [Site oficial do Windhawk](https://windhawk.net/)
- [Repositório Windhawk no GitHub](https://github.com/ramensoftware/windhawk)
- [Documentação Firefox UserChrome](https://www.userchrome.org/)

### Comunidades
- [Subreddit r/Windhawk](https://www.reddit.com/r/windhawk/)
- [Subreddit r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS/)
- [Comunidades de customização do Windows 11](https://www.reddit.com/r/windows11/)

### Inspiração
- [DeviantArt - Windows Customization](https://www.deviantart.com/tag/windowscustomization)
- [/r/unixporn para Linux](https://www.reddit.com/r/unixporn/) (inspiração para temas Windows)

## 📝 Licença

Licença MIT - Veja o arquivo [LICENSE](LICENSE) para detalhes

## 🤝 Contribuindo

Este é um guia pessoal, mas sugestões e melhorias são bem-vindas! Sinta-se à vontade para:
- Fazer um fork deste repositório
- Enviar issues para correções ou adições
- Compartilhar suas próprias dicas de customização

---

**Aproveite sua experiência Windows bonita e translúcida!** 🎨✨
