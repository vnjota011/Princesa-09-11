# Princesa — 09/11

## Como abrir
1. Extraia o ZIP inteiro.
2. Abra index.html no Chrome, Edge ou Firefox.

Não precisa instalar Node ou bibliotecas. Para editar, abra a pasta no VS Code. O Live Server é opcional.

## Arquivos
- index.html: estrutura da página.
- style.css: layout e cores.
- script.js: desenho e animações em Canvas 2D.
- assets/princesa.webp: imagem da personagem.
- assets/musica.mp3: música reproduzida em loop.
- ABRIR-PREVIA.html: exportação da prévia com a imagem incorporada.

O projeto principal (index.html) funciona sem internet e sem dependências externas. A música tenta iniciar automaticamente e toca em loop. Alguns navegadores podem bloquear áudio automático até uma interação do visitante.

## Personalizar
No script.js:
- Procure lettering('09/11' para mudar a data. O mapa font define os caracteres disponíveis; adicione outros números se necessário.
- length:24 controla a quantidade de vaga-lumes.
- moveFlies controla trajetórias, velocidades e pausas individuais.
- beam e pool controlam a iluminação e o brilho no chão.
- breath controla a respiração; glyph define os Zzz.

A data é decorativa: não existe contagem regressiva nem liberação automática.
A personagem usa uma imagem com movimento sutil de respiração, não uma sequência de sprites desenhados.
As animações começam automaticamente ao abrir a página.

## Usar em outro site
Copie esta pasta e incorpore index.html em um iframe, ou integre o conteúdo de main, o CSS e o JavaScript, ajustando o caminho assets/princesa.webp conforme a página de destino.

Última versão: luz conectada ao chão, Zzz, reticências e vaga-lumes com movimento independente.
