# Jogo da Velha (Tic-Tac-Toe) — React + Vite

**Projeto:** Jogo da Velha implementado em React usando Vite — prática para aprender componentes, estado, hooks e estilos modernos.

---

## 🚀 Visão geral
Este repositório contém uma implementação completa do clássico **Jogo da Velha** (Tic-Tac-Toe) com:

- Alternância entre **X** e **O**
- Detecção de vencedor e destaque da linha vencedora
- Detecção de empate
- Histórico de jogadas (navegável)
- Placar persistente (armazenado em `localStorage`)
- Botões: **Reiniciar rodada** e **Resetar placar**
- Estilos modernos e animações CSS

---

## 🧩 Estrutura do projeto
```
tic-tac-toe/
├─ package.json
├─ vite.config.js
├─ index.html
└─ src/
   ├─ main.jsx
   ├─ App.jsx
   ├─ styles.css
   └─ components/
      ├─ Board.jsx
      └─ Square.jsx
```

---

## 💻 Tecnologias
- React 18
- Vite
- JavaScript (ESModules)
- CSS puro (estilos e animações)

---

## 🧭 Como rodar localmente

1. Clone o repositório (ou baixe e extraia os arquivos):
```bash
git clone [https://github.com/SEU-USERNAME/SEU-REPO.git](https://github.com/alaxfernando947-png/Desenvolvimento-aplica-o-React-Jogo-da-Velha-Tic-Tac-Toe-)
cd SEU-REPO
```

2. Instale dependências:
```bash
npm install
```

3. Rode em modo de desenvolvimento:
```bash
npm run dev
```

4. Abra no navegador a URL indicada pelo Vite (ex.: `http://localhost:5173/`).

---

## 📦 Build para produção
```bash
npm run build
npm run preview
```
O diretório `dist/` conterá os arquivos prontos para deploy.

---

## ☁️ Deploy (recomendado)
- **Vercel** — integração automática com GitHub (recomendado).
- **GitHub Pages** — via `gh-pages` (configurar `homepage` no `package.json`).
Se quiser, eu te passo o passo a passo para publicar em Vercel ou GitHub Pages.

---

## 🧠 Principais aprendizados
- Componentização (separação `Board` e `Square`)
- Gestão de estado com `useState`
- Manipulação de eventos (cliques, histórico)
- Uso de `localStorage` para persistência simples
- Estilização e animações CSS modernas

---

## 🛠️ Melhoria possíveis (próximos passos)
- Modo jogador vs IA (algoritmo Minimax)
- Persistência do histórico no `localStorage`
- Temas (claro/escuro)
- Animações e sons adicionais
- Acessibilidade (aria-labels, foco por teclado)

---

## ✍️ Créditos
Desenvolvido por: **ÁLAX FERNANDO DE FREITAS NUNES**  
Projeto feito como prática de React + Vite.

---

## 📄 Licença
Este projeto está livre para uso educacional. Coloque aqui a licença desejada (ex.: MIT) se quiser tornar explícito.


