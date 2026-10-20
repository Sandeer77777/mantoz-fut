# Mantoz Fut

Catálogo de camisas de futebol da Mantoz Fut. Site estático (HTML, CSS e JavaScript em um arquivo) que lê `produtos.json`. As fotos ficam no Cloudflare R2.

## Arquivos
- `index.html`: catálogo, página do produto, guia de tamanhos, carrinho e promoção.
- `produtos.json`: lista de produtos, com preço, categoria, liga e links das fotos.
- `logo-mantoz.png`, `favicon.png`, `hero.jpg`, `guia-tamanhos.webp`: imagens do site.

## Rodar localmente
```bash
python -m http.server 8080
```
Depois abra http://localhost:8080/index.html
