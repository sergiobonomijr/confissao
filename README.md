# Exame de Consciência

Portal para preparação da Confissão. Conduz um exame de consciência pergunta a pergunta e, ao final, reúne as respostas em dois textos: um roteiro enxuto para ler diante do sacerdote e um texto mais longo para a meditação.

**Acesse:** https://sergiobonomijr.github.io/exame-de-consciencia/

## Como funciona

**O exame** — 40 perguntas, uma por tela, agrupadas em dez blocos: a última confissão, os dez mandamentos e um bloco final sobre trabalho, tempo e caridade. Todas em forma negativa, de modo que "sim" sempre significa falta.

As escalas variam conforme a pergunta. A maioria oferece *não / uma vez ou outra / com frequência*; as que só admitem sim ou não — comunhão em pecado grave, circunstância agravante, fidelidade conjugal, atentado contra a vida — mostram apenas duas opções. A primeira pergunta aceita a data da última confissão em DD/MM/AAAA e calcula os dias exatos, ou as opções *menos de um mês / alguns meses / mais de um ano / não me recordo*.

Cada pergunta aceita uma anotação livre, que reaparece no texto final. No computador, as teclas 1, 2 e 3 respondem.

**O resultado** — duas vistas, alternadas por um botão:

- **Roteiro** — a versão curta. Oração de abertura, a fórmula "Abençoe-me, padre" já com o tempo desde a última confissão, os pecados numerados (os graves primeiro, com a frequência indicada e as anotações), a fórmula de encerramento e o Ato de Contrição.
- **Meditação** — o texto longo. Uma reflexão por mandamento tocado, o que a consciência apontou, um propósito concreto para cada bloco, os pontos em que nada pesou e um roteiro do momento da confissão.

O roteiro pode ser baixado em PDF (formato A5, bom para o bolso), impresso ou copiado.

## Privacidade

Tudo acontece no navegador. Não há servidor, banco de dados nem envio de informação: as respostas existem apenas na memória da página e desaparecem quando ela é fechada. O PDF é gerado no próprio dispositivo.

## Técnico

Arquivo único (`index.html`), sem build e sem dependências de instalação. A única biblioteca externa é o [jsPDF](https://github.com/parallax/jsPDF), carregado por CDN para a exportação do roteiro; sem ela, o botão recorre à impressão do navegador. Tema claro e escuro conforme a preferência do sistema, e folha de estilo própria para impressão.

## Fontes

As perguntas foram redigidas a partir de:

- [Exame de consciência para a confissão (adultos)](https://opusdei.org/pt-br/article/exame-de-consciencia-para-a-confissao-adultos/) — Opus Dei
- [As 30 perguntas propostas pelo Papa Francisco](https://www.ocapuchinho.com.br/noticias/papa-francisco-propoe-estas-perguntas-para-um-bom-exame-de-consciencia/arcanjo) para um bom exame de consciência

Este é um auxílio à preparação pessoal, não um documento de autoridade eclesial.
