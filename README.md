# Link na bio — Lia Chinellato

Página única, sem dependências, com os links do Instagram da Lia:

- **Giro de Ideias** → https://girodeideias.liacreator.com/
- **Diagnóstico Gratuito** → https://form.respondi.app/GRGsgSds

## Rodar localmente

Abrir `index.html` direto no navegador (duplo clique). Não precisa de servidor,
Node.js ou build — HTML + CSS puro.

## Editar os links

Os dois cards (`.banner`) estão em `index.html`, dentro de `<main class="lista-links">`.
Cada um é um `<a>` com `href`, uma etiqueta, título, texto de apoio e seta. Pra
adicionar um novo link, copiar a estrutura de um `<a class="banner">` existente.

## Identidade visual

Mesma paleta e tipografia do Giro de Ideias — creme `#FFFDEC`, vinho `#502533`,
rosa `#FF9DD9`, verde-lima `#C1FF72`, fontes Bodoni Moda + DM Sans (Google
Fonts). Detalhes em `css/estilo.css`.

## Deploy

Hospedagem estática gratuita (GitHub Pages ou Netlify), apontando o subdomínio
`bio.liacreator.com` pra esse projeto — mesmo modelo usado no Giro de Ideias.
