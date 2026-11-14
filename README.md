# Carteira — visualizador pessoal

Aplicativo independente, mobile-first, com a estrutura de navegação da referência: abas Frente, Verso e QR Code; cabeçalho com voltar/compartilhar/opções; navegação inferior Carteira, Serviços e Opções.

## Imagens pessoais

A pessoa escolhe as imagens da frente e do verso pelo seletor do próprio dispositivo. As imagens são processadas e armazenadas **somente no armazenamento local do navegador (localStorage)**. Elas não são enviadas ao GitHub nem a servidores externos. Limite de arquivo: 12 MB por imagem; a capacidade efetiva do armazenamento local pode variar conforme navegador e dispositivo.

Para remover imagens, use os botões exibidos sobre a imagem ou acesse Opções. Limpar os dados do navegador também remove as imagens salvas.

## Executar localmente

Abra `index.html` ou sirva os arquivos com servidor estático. Para recursos PWA/service worker, use HTTPS (GitHub Pages fornece HTTPS).

## GitHub Pages

Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Privacidade

Este é um visualizador local, não um cofre criptografado e não realiza autenticação, sincronização ou backup. Para documentos sensíveis, use um dispositivo confiável e evite compartilhar capturas de tela. O QR Code é apenas ilustrativo e não valida identidade.
