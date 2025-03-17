# Explorando Recursos de IA Generativa com Azure Computer Vision e Copilot

Este repositório contém um projeto de reconhecimento de texto em imagens utilizando o Azure Computer Vision e o Copilot.

## Estrutura do Repositório
- **inputs/**: Pasta contendo as imagens utilizadas para o reconhecimento de texto.
- **outputs/**: Pasta contendo os resultados do reconhecimento de texto em formato JSON.

## Processo
1. Utilizei o Copilot para gerar duas imagens contendo textos.
2. Utilizei o Azure Computer Vision para extrair o texto das imagens.
3. Os resultados foram salvos em arquivos JSON na pasta `outputs`.

## Insights
- O Azure Computer Vision foi eficaz na extração de texto, mas em alguns casos a confiança foi baixa (ex: "HLERTA" com 0.298 de confiança).
- O uso de polígonos limitadores permite identificar a localização exata do texto na imagem.

## Possibilidades
- Automatizar a extração de texto de documentos escaneados.
- Integrar o reconhecimento de texto em aplicações de automação de processos.

## Resultados
### Imagem 1
- Texto extraído: "NOME"
- Confiança: 0.989

### Imagem 2
- Textos extraídos: "ITHHIS", "ADO HLERTA", "MATHEUS"
- Confianças: 0.652, 0.666, 0.731

## Prints
![Imagem 1](inputs/imagem1.jpg)
![Imagem 2](inputs/imagem2.jpg)
