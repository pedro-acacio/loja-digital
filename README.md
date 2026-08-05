# Loja Digital

Protótipo estático de uma loja virtual, em HTML e CSS puros. Por enquanto existe apenas a página inicial (um link para login) e a tela de login/cadastro, com formulário de e-mail e senha, opções de login social (Gmail/Facebook, sem funcionalidade real) e um rodapé com links institucionais e de categorias — todos ainda como placeholders (`href="#"`). Não há backend, JavaScript de interação ou persistência de dados.

## Tecnologias

- HTML5 e CSS3 puro (aninhamento de seletores nativo do CSS moderno)
- Sem framework, sem build, sem dependências externas

## Estrutura

- `index.html` — página inicial, com link para a tela de login
- `src/pages/login.html` — formulário de login/cadastro e rodapé do site
- `src/styles/global.css` / `reset.css` — estilos e reset de CSS
- `src/assets/` — logos e ícones (SVG) usados nas páginas

## Como rodar

Não há build nem dependências. Basta abrir `index.html` diretamente no navegador ou servir a pasta com um servidor estático (ex: `npx serve .`).
