# 🎓 Site Estudantil — IARLEMG

Portal estudantil desenvolvido com **React + Vite + MUI (Material UI)**.

---

## 🚀 Rodando o projeto localmente

### Pré-requisitos
- [Node.js](https://nodejs.org/) versão 18 ou superior
- npm (já vem com o Node)

### Passos

```bash
# 1. Entre na pasta do projeto
cd site-estudantil

# 2. Instale as dependências
npm install

# 3. Inicie o servidor de desenvolvimento
npm run dev
```

Acesse em: **http://localhost:5173**

---

## 📁 Estrutura do projeto

```
site-estudantil/
├── public/
├── src/
│   ├── assets/
│   │   └── logo.png          ← Logo IARLEMG
│   ├── components/
│   │   └── Navbar.jsx        ← Barra de navegação
│   ├── pages/
│   │   ├── Home.jsx          ← Página inicial
│   │   ├── Blog.jsx          ← Recursos / cards
│   │   ├── Sobre.jsx         ← Sobre o campus
│   │   └── Contato.jsx       ← Formulário de contato
│   ├── App.jsx               ← Rotas
│   ├── main.jsx              ← Entrada
│   └── index.css             ← Estilos globais
├── index.html
├── package.json
└── vite.config.js
```

---

## 📤 Publicando no GitHub

### 1. Crie um repositório no GitHub
- Acesse [github.com](https://github.com)
- Clique em **"New repository"**
- Dê um nome (ex: `site-estudantil`) e clique em **"Create repository"**

### 2. Inicialize o Git na pasta do projeto

```bash
# Dentro da pasta site-estudantil:
git init
git add .
git commit -m "primeiro commit - site estudantil IARLEMG"
```

### 3. Conecte ao repositório remoto

```bash
git remote add origin https://github.com/SEU_USUARIO/site-estudantil.git
git branch -M main
git push -u origin main
```

> Substitua `SEU_USUARIO` pelo seu usuário do GitHub.

### 4. Para atualizações futuras

```bash
git add .
git commit -m "descrição da mudança"
git push
```

---

## 🌐 Deploy gratuito com Vercel ou Netlify

### Vercel (recomendado)
1. Acesse [vercel.com](https://vercel.com)
2. Clique em **"Import Project"** → selecione o repositório
3. Clique em **"Deploy"** — pronto! ✅

### Netlify
1. Acesse [netlify.com](https://netlify.com)
2. Clique em **"Import from Git"** → selecione o repositório
3. Configure: **Build command:** `npm run build` | **Publish dir:** `dist`
4. Clique em **"Deploy site"** ✅

---

## 🎨 Paleta de cores

| Cor | Hex |
|-----|-----|
| Laranja principal | `#E87722` |
| Laranja escuro | `#c45e0a` |
| Laranja claro | `#f59a4f` |
| Preto/fundo | `#1A1A1A` |
| Card | `#2a2a2a` |
| Texto secundário | `#b0b0b0` |

---

## 🛠 Tecnologias utilizadas

- [React 18](https://react.dev)
- [Vite 6](https://vite.dev)
- [Material UI v6](https://mui.com)
- [React Router v6](https://reactrouter.com)
