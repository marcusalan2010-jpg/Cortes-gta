# GTA Cut Studio

Editor de trechos de gameplay de GTA 5 para YouTube Shorts, TikTok e YouTube.

## Como usar

Baixe este repositório em **Code → Download ZIP**, extraia e abra `output/GTA-Cut-Studio.html` no Chrome ou Edge atualizado, preferencialmente no computador. Esse arquivo reúne o programa completo e funciona sem instalação.

Também é possível abrir `index.html`, mantendo `style.css` e `app.js` na mesma pasta.

1. Importe seu vídeo.
2. Marque o início e o fim em segundos, pelos botões ou pelos atalhos **I** e **O**. Use espaço para reproduzir ou pausar.
3. Escolha o formato vertical para Shorts/TikTok ou preserve o formato original para YouTube.
4. Ajuste o enquadramento e, se quiser, adicione um título ao vídeo.
5. Adicione os trechos à lista e exporte cada corte.

## Exportação e privacidade

- Os vídeos são processados no dispositivo, sem upload.
- A exportação ocorre em tempo real; mantenha a aba visível até terminar.
- MP4 é usado quando suportado pelo navegador. Caso contrário, o resultado é WebM e pode exigir conversão para MP4 antes de postar.
- A lista é temporária: fechar a página ou importar outro vídeo apaga os cortes da sessão.
- A seleção dos melhores momentos é manual.

## Arquivos

- `index.html`, `style.css`, `app.js`: código-fonte do editor.
- `output/GTA-Cut-Studio.html`: versão independente, em um único arquivo.
- `output/GTA-Cut-Studio.zip`: pacote com o programa independente e instruções.

## Validação

Sintaxe JavaScript e referências dos controles verificadas. Reprodução e exportação ainda precisam de teste em um navegador com vídeo real. A interface pode carregar fontes do Google Fonts quando aberta pela versão de código-fonte; o arquivo independente usa fontes locais.
