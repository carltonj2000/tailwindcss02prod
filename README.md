# Tailwind CSS

## Videos Tailwind CSS: From Zero to Production

### 07: Customizing Your Design System

```bash
rsync -a --exclude node_modules --exclude build ./video6/ ./video7/
npx tailwindcss init tailwind-full.config.js --full
```

### 06: Extracting Reusable Components

```bash
rsync -a --exclude node_modules --exclude build ./video5/ ./video6/
npm i react react-dom
npm i -D @vitejs/plugin-react-refresh
npm i -g http-server
npx vite build
cd dist; ln -s ../img; http-server
```

### 05: Composing Utilities with @apply

```bash
rsync -a --exclude node_modules --exclude build ./video3/ ./video5/
```

### 03: Responsive Design & 04: Hover, Focus and Other States

```bash
rsync -a --exclude node_modules --exclude build ./video2/ ./video3/
```

### 02: The Utility-First Workflow 

```bash
rsync -a --exclude node_modules --exclude build ./video1/ ./video2/
```

### 01: Setting Up Tailwind CSS

```bash
npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css # manual build
npm init -y
npx tailwindcss init -p
```

## History

The code in this repo is base on the
[Tailwind CSS: From Zero to Production](https://youtu.be/qYgogv4R8zg)
video.