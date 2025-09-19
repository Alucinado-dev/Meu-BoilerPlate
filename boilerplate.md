# Meu Boilerplat Oficial

## Instalações de coisas com react

### Criar projeto react + Vite  

npx  create-vite@latest .  --template react-ts
     *entrar no arquivo criado
npm install
npm run dev

### instalar Dependencias de Dev

npm install --save-dev prettier eslint-config-prettier typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-simple-import-sort

### instalar FontAwesome

npm install --save @fortawesome/fontawesome-svg-core
npm install --save @awesome.me/kit-db1c54e319
npm install --save @fortawesome/react-fontawesome@latest

### instalar  Tailwind

npm install tailwindcss @tailwindcss/vite
no index.css adicionar `@import 'tailwindcss'`

### instalar Lucide Icons

npm install lucide-react

### instalar UID (gerador de ID)

npm install uuid
import { v4 as idGenerator } from 'uuid';

### instalar reacts router

npm i react-router

import {
  createBrowserRouter,
  RouterProvider,
} from "react-router";

import React from "react";
import ReactDOM from "react-dom/client";

const router = createBrowserRouter([
  {
    path: "/",
    <!-- element: <div>Hello World</div>, -->
  },
]);

const root = document.getElementById("root");

ReactDOM.createRoot(root).render(
  <!-- <RouterProvider router={router} /> -->
);

## no HTML

<!-- <script src="https://cdn.counter.dev/script.js" data-id="33f78ff6-536a-45bc-92b9-1b262ec69e8d" data-utcoffset="-3"></script> -->
