# Exame de Consciência

Portal em página única para preparar a Confissão: 40 perguntas curtas percorrendo
os mandamentos, uma de cada vez. Ao final, reúne o que a consciência apontou em
duas vistas — **Roteiro** (para levar ao confessionário) e **Meditação** (texto
mais longo, com propósitos por mandamento) — com opções de imprimir, copiar e
baixar em PDF.

**Acesso:** https://confissao.online

## Privacidade

Nada é enviado a servidor algum. Todas as respostas ficam apenas na memória do
navegador e desaparecem ao fechar a página. Não há cookies, analytics nem
armazenamento local.

## Domínio

O site é servido pelo GitHub Pages a partir do branch `main`, com domínio
próprio (`confissao.online`, registrado na Namecheap) apontado por quatro
registros A para `185.199.108-111.153` e um CNAME de `www` para
`sergiobonomijr.github.io`. O arquivo `CNAME` na raiz deste repositório amarra
o domínio ao site — não o remova.

## Técnico

Arquivo único (`index.html`), sem build e sem dependências além do
[jsPDF](https://github.com/parallax/jsPDF) via CDN, usado só para gerar o PDF do
roteiro. Suporta modo claro/escuro do sistema e possui folha de estilo de
impressão.
