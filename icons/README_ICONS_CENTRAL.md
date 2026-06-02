# Pacote de ícones da Central

Estrutura sugerida no repositório GitHub Pages:

index.html
manifest.json
service-worker.js
README.md
icons/
  icon-192x192.png
  icon-512x512.png
  apple-touch-icon.png
  favicon.ico
  favicon-16x16.png
  favicon-32x32.png
  ...demais tamanhos

No <head> do index.html, usar:
<link rel="manifest" href="./manifest.json">
<link rel="apple-touch-icon" href="./icons/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="./icons/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="./icons/favicon-16x16.png">
<meta name="theme-color" content="#0f5132">

Suba a pasta icons inteira.
