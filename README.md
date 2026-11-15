# Web App Heloísa Muniz

Mídia kit de patrocínio da atleta de jiu-jitsu **Heloisa Muniz**, em formato de site responsivo, com a mesma identidade visual do material em PSD.

## O que tem no site

- **Capa:** logo "Mídia Kit / Heloisa Muniz", foto da atleta e faixa lateral animada "JIU-JITSU".
- **Quem é a Heloisa:** apresentação, idade, faixa, equipe e cidade.
- **No Tatame:** conquistas de 2026 e fotos dos campeonatos.
- **Próximos desafios:** linha do tempo dos campeonatos da temporada, com contagem de dias até cada um (e "realizado" depois que a data passa).
- **Por que a Heloisa:** visibilidade, propósito e proximidade.
- **Cotas de patrocínio** (Ouro R$ 500, Prata R$ 300, Bronze R$ 150, Apoiador R$ 50) e a lista de apoios aceitos em produtos e serviços. O botão "Quero esta cota" já leva a cota escolhida para o formulário de contato.
- **Sua marca no kimono:** o patrocinador escolhe onde a marca aparece, envia a própria logo e vê como fica.
- **Contato:** formulário que monta a proposta e abre o WhatsApp com a mensagem pronta.

## Como editar os textos

Todo o conteúdo fica em **`content.json`**: textos, datas e nomes dos campeonatos, valores das cotas, produtos e serviços aceitos e contatos. Para mudar alguma coisa:

1. Abra o `content.json` aqui no GitHub e clique no lápis (Editar).
2. Troque o texto entre aspas. Por exemplo, `"telefone": "(11) 9 1111 - 1111"`.
3. Clique em **Commit changes**. O site se atualiza sozinho em cerca de 1 minuto.

Dicas:

- Datas dos campeonatos no formato `dd/mm`, por exemplo `"15/03"`. O ano usado na contagem de dias fica em `"ano"`.
- `**texto**` deixa um trecho em destaque.
- Se o valor de uma cota ficar vazio (`""`), o site mostra "sob consulta".

## Estrutura

```
index.html     página, estilos e scripts
content.json   conteúdo editável
img/           imagens extraídas do PSD e do PPTX (webp)
```

Site estático, sem dependências nem etapa de build. As fontes vêm do Google Fonts.
