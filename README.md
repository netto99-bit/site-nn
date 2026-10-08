# NN Engenharia — site institucional

Site responsivo em português, com a identidade verde-escura do projeto original. Construído com Astro e CSS próprio, com saída estática.

## Desenvolvimento

Requisitos: Node.js 22.12+ (versão LTS) e npm.

```sh
npm ci
npm run dev
npm run build
npm run preview
```

## Publicação na Vercel

Repositório: `netto99-bit/site-nn`. Projeto existente: `site-nn`.
Framework: Astro. Comando de build: `npm run build`. Diretório de saída: `dist`.
O arquivo `vercel.json` define esses parâmetros. O `package-lock.json` fixa as dependências.

## Atendimento

O formulário prepara um pedido no navegador e permite copiar o texto. Não envia dados a um servidor, não registra leads e não simula uma solicitação recebida.

Para habilitar WhatsApp, configure `PUBLIC_WHATSAPP` com o número comercial validado (código do país + DDD + número, apenas dígitos) e publique novamente. Exemplo de estrutura de variável em `.env.example`; nenhum número de atendimento foi inventado. A mensagem é revisada pelo visitante antes de abrir o WhatsApp.

## Conteúdo e identidade

- Página principal: `src/pages/index.astro`.
- Estilos e adaptação mobile: `src/styles/global.css`.
- Símbolo tipográfico NN e ilustração arquitetônica vetorial conceitual; não representam logotipo oficial fornecido ou obra executada.
- Sem portfólio, depoimentos, números de clientes, endereço ou credenciais profissionais não confirmados.
- Validar descrições comerciais com a empresa e acrescentar telefone oficial, logotipo e fotos reais quando disponíveis.

## Privacidade e acessibilidade

Sem analytics, cookies de rastreamento, fontes remotas ou banco de dados. Campos preenchidos permanecem somente na página até o visitante copiar ou compartilhar. Navegação por teclado, link de salto, rótulos visíveis, menu com estado acessível e respeito à preferência por movimento reduzido.
