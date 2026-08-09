# Simulado TVDE — PWA

Esta pasta contém a versão PWA do Simulado TVDE com as 316 questões.

## Publicar gratuitamente com GitHub Pages

1. Crie um repositório no GitHub (por exemplo: `simulado-tvde`).
2. Envie TODOS os arquivos desta pasta para a raiz do repositório:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - pasta `icons`
3. No GitHub: Settings → Pages.
4. Em Build and deployment, selecione:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
5. Salve e aguarde a publicação.
6. Abra o endereço HTTPS gerado pelo GitHub Pages no Safari do iPhone.
7. No Safari: Compartilhar → Adicionar à Tela de Início.

A PWA precisa ser servida por HTTPS (como GitHub Pages) para o Service Worker funcionar.
