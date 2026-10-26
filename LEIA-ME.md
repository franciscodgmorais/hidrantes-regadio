# Hidrantes do Regadio — Belmonte

Primeiro protótipo gratuito de uma aplicação web instalável (PWA), com os 7 pontos importados do GPX fornecido.

## Incluído
- Lista pesquisável de hidrantes.
- Ficha com latitude, longitude e coordenadas.
- Esquema visual offline dos pontos (não representa estradas).
- Botão para abrir o destino no Google Maps.
- Cache dos ficheiros da aplicação para consulta offline depois da primeira abertura online.

## Limitação importante
O GPX contém coordenadas e nomes, mas não contém cartografia rodoviária. Por isso, o mapa desta versão é um esquema relativo offline, não um mapa de estradas. Para ter estradas reais offline, será necessário preparar uma área cartográfica offline e verificar os respetivos termos de utilização. A navegação no Google Maps pode exigir Internet; para utilização sem rede, descarregue previamente a área no Google Maps e teste o percurso.

## Como publicar gratuitamente com GitHub Pages
1. Crie uma conta em https://github.com/ se ainda não tiver.
2. Crie um repositório novo, por exemplo `hidrantes-regadio`.
3. Carregue os ficheiros `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg` para a raiz do repositório.
4. Nas definições do repositório, abra **Pages** e escolha a publicação a partir da branch principal (root).
5. Abra o endereço HTTPS gerado no telemóvel com Internet.
6. Android/Chrome: menu ⋮ > **Instalar app** ou **Adicionar ao ecrã principal**.
   iPhone/Safari: botão Partilhar > **Adicionar ao ecrã principal**.
7. Abra a app uma vez com Internet e teste o modo de avião para confirmar a consulta offline.

## Segurança operacional
Antes de utilização operacional, confirme em campo as coordenadas, o acesso, o tipo de ligação, caudal/pressão quando conhecido, estado do ponto e restrições. Esta versão é um protótipo e não substitui a validação operacional.
