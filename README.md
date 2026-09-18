# SoundREI — Landing Page V2

Landing page oficial da **SoundREI — Sonorização, Manutenção, Locação e Projetos de Áudio**.

## V2

A V2 consolida a marca em quatro pilares:

1. Sonorização profissional
2. Manutenção & reparo
3. Locação de equipamentos
4. Projetos & instalação

Inclui identidade preto/dourado, layout responsivo, catálogo por aplicação, processo técnico, referências de preço, FAQ e geração de orçamento via WhatsApp.

## Configurar contatos

Edite `config.js`:

```js
window.SOUNDREI_CONFIG = {
  whatsapp: "5521999999999",
  instagram: "@soundrei",
  email: "contato@soundrei.com.br"
};
```

O WhatsApp deve conter apenas números, incluindo país e DDD.

## GitHub Pages

O site é estático e pode ser servido diretamente da branch `master`.

1. Abra **Settings → Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Selecione `master` e `/ (root)`.
4. Salve.

URL publicada pelo GitHub Pages:

`https://az1nn.github.io/sound-rei/`

## Stack

HTML5 + CSS3 + JavaScript puro. Sem framework, build ou dependências externas.

## Observação

Os valores exibidos são referências comerciais e não substituem orçamento por escopo.


## Discoverability

A V2.1 adiciona canonical URL, favicon vetorial, Open Graph URL/locale, robots.txt, sitemap.xml e dados estruturados LocalBusiness sem publicar os contatos mock como dados comerciais reais.
