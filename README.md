# RESPAW XITER — PWA

Painel web instalável para iPhone, desenvolvido para funcionar a partir de um PC Windows e hospedado no GitHub Pages.

## Arquivos
- `index.html`: interface, alternadores e FOV.
- `manifest.json`: metadados de instalação PWA.
- `service-worker.js`: cache dos arquivos para oferecer suporte offline após a primeira visita.
- `icons/icon.svg`: ícone vetorial.

## Publicar no GitHub Pages
1. Abra **Settings** neste repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)).
5. Clique em **Save**.
6. Aguarde o GitHub concluir a publicação. O endereço esperado é:
   `https://souzarlk.github.io/respaw-xiter/`

## Instalar no iPhone
1. Abra o endereço publicado no Safari do iPhone.
2. Toque em **Compartilhar**.
3. Escolha **Adicionar à Tela de Início**.
4. Confirme em **Adicionar** e abra pelo novo ícone.

## Configurações e privacidade
Os estados dos sete alternadores e o FOV são guardados em `localStorage` no próprio navegador/dispositivo. Limpar os dados do site pode apagar essas configurações. Não há conta, servidor de usuário ou envio dessas preferências para terceiros.

## Limites de integração
O painel não injeta códigos, não lê ou modifica a memória do Free Fire e não altera o jogo. Os interruptores e o FOV são controles locais da interface. O botão de iniciar apenas tenta abrir o esquema de URL `freefire://`; a disponibilidade depende de o jogo reconhecer esse esquema na versão instalada.
