# Dias Gomes Advocacia — LP Auxílio-Moradia

Landing page estática (HTML puro, sem dependências de build) para captação de leads sobre auxílio-moradia de médicos residentes.

## Arquivos
- `index.html` — página principal
- `redirect.html` — página de redirecionamento pós-formulário (WhatsApp com mensagem pré-preenchida)

## Deploy no Vercel
1. Suba este repositório no GitHub (veja comandos abaixo).
2. Em vercel.com → **Add New Project** → importe o repositório.
3. Como é HTML estático, não é necessário configurar build command nem output directory — o Vercel detecta automaticamente.
4. Deploy.

## Antes de publicar
- Troque o número de WhatsApp placeholder `5500000000000` (aparece em `index.html` e `redirect.html`) pelo número real do escritório.
