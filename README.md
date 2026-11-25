# CuidarBem — protótipo de cuidados domiciliares

Protótipo acadêmico (React + TypeScript + Tailwind CSS + Lucide Icons). Sem backend: os dados ficam no `localStorage`.
**Todos os dados médicos são fictícios** e não representam prescrições ou orientações reais.

## Como executar
Requer Node.js 18+.

    npm install
    npm run dev       # http://localhost:5173
    npm run build     # gera a pasta dist/

## Estrutura
- `src/App.tsx` — telas, componentes, dados de demonstração e lógica
- `src/main.tsx` — ponto de entrada
- `src/index.css` — Tailwind

## Dica
Em Configurações há o botão "Restaurar dados fictícios". Para recomeçar, limpe o localStorage (chave `cuidarbem.v1`).
