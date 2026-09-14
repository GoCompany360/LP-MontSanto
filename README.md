# Residencial Mont'Santo — Landing Page

Identidade visual própria do Mont'Santo (laranja da marca + neutros quentes + espresso;
tipografia Lora (serifada tradicional) + Archivo + Manrope; texto sem travessoes), com a mesma estrutura/diagramação da LP Infinity.

LP do Residencial Mont'Santo (Souza Eng.Arq · Santa Maria/RS), criada a partir da
mesma diagramação da LP Infinity Residence da GO Company 360.

## Como publicar (igual à Infinity, via GitHub Pages)
1. Crie um repositório novo (ex.: `LP-MontSanto`) e envie todo o conteúdo desta pasta
   (`index.html` + pasta `img/`).
2. Em *Settings → Pages*, publique a branch principal (`/root`).
3. A LP ficará no ar em `https://<usuario>.github.io/LP-MontSanto/`.

Tudo é um único arquivo `index.html` (HTML + CSS + JS embutidos) + a pasta `img/`.

## Conteúdo / dados usados
- 59 unidades · 14 pavimentos · 4 elevadores · 128 boxes + 59 homeboxes · +900 m² de área social
- Tipologias 124–248 m² (finais 01–06 do 4º ao 13º; coberturas 1401–1404 no 14º)
- Endereço: Av. Nossa Senhora da Medianeira, 1130, esq. Rua Dr. Zamenoff — Bairro Medianeira
- 24 imagens (renders) do Drive, otimizadas para web (renomeadas `ms-*.jpg`)
- WhatsApp dos leads: **55 55 99605-6881** (GO Company 360) — variável `WNUM` no `<script>`
- Instagram: @residencial_montsanto

## Como ajustar
- **WhatsApp:** edite `var WNUM='5555996056881'` no bloco `<script>`.
- **Mapa:** o iframe do Google Maps aponta para o endereço; ajuste o `src` se quiser um pin exato.
- **Vídeo / Tour 360º:** não incluídos (a combinar). É só adicionar uma seção depois.
- **Logo:** logo oficial (img/logo-montsanto*.png) — versão clara para fundo escuro e original para fundo claro.
