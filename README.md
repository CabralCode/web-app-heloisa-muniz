# Web App Heloísa Muniz

Mídia kit de patrocínio da atleta de jiu-jitsu **Heloisa Muniz**, em formato de site responsivo, com a mesma identidade visual do material em PSD.

## O que tem no site

- **Capa:** logo "Mídia Kit / Heloisa Muniz" e faixa lateral animada "JIU-JITSU".
- **Quem é a Heloisa:** apresentação, idade, faixa, equipe e cidade.
- **No Tatame:** conquistas de 2026 e fotos dos campeonatos.
- **Próximos desafios:** linha do tempo da temporada. Quando a data de um campeonato é preenchida, o cartão mostra quantos dias faltam.
- **Por que a Heloisa:** visibilidade, propósito e proximidade.
- **Cotas de patrocínio** (Ouro, Prata, Apoio): ao escolher uma cota, as áreas que ela cobre ficam em destaque. O simulador calcula o investimento pelo número de campeonatos.
- **Sua marca no kimono:** o patrocinador escolhe onde a marca aparece, envia a própria logo e vê como fica.
- **Contato:** formulário que monta a proposta e abre o WhatsApp com a mensagem pronta.

## Como editar os textos

Todo o conteúdo fica em **`content.json`**: textos, datas e nomes dos campeonatos, valores das cotas, custo médio por campeonato e contatos. Para mudar alguma coisa:

1. Abra o `content.json` aqui no GitHub e clique no lápis (Editar).
2. Troque o texto entre aspas. Por exemplo, `"telefone": "(11) 9 1111 - 1111"`.
3. Clique em **Commit changes**. O site se atualiza sozinho em cerca de 1 minuto.

Dicas:

- Datas dos campeonatos no formato `dd/mm`, por exemplo `"15/03"`.
- `**texto**` deixa um trecho em destaque.
- Se o valor de uma cota ficar vazio (`""`), o site mostra "sob consulta".

## Estrutura

```
index.html     página, estilos e scripts
content.json   conteúdo editável
img/           imagens extraídas do PSD (webp)
```

Site estático, sem dependências nem etapa de build. As fontes vêm do Google Fonts.
