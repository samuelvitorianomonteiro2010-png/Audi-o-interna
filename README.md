# Laboratório de Silêncio

Protótipo experimental para praticar memória e previsão musical com trechos de silêncio progressivo. Sua eficácia para desenvolver audição interna ainda não foi demonstrada.

## Baixar e usar

1. [Baixe o arquivo Laboratorio-de-silencio.html](https://github.com/samuelvitorianomonteiro2010-png/Audi-o-interna/raw/refs/heads/main/Laboratorio-de-silencio.html). Se o navegador mostrar o código, salve a página como `Laboratorio-de-silencio.html`.
2. Abra o arquivo salvo em um navegador atualizado, como Chrome, Edge ou Firefox.
3. Ajuste o volume e clique em **Começar sessão**. Não é necessário instalar programas, criar conta ou manter conexão com a internet.

Outra opção: na página do repositório, selecione **Code → Download ZIP**, extraia o arquivo e abra `Laboratorio-de-silencio.html`.

## Funcionamento

Você ouve uma frase completa e, depois, uma versão com as últimas notas em silêncio. Continue a frase mentalmente e compare a nota de conferência com a última nota esperada. Na prática adaptativa, três acertos consecutivos aumentam o silêncio e um erro o reduz. Na sondagem fixa, quatro notas ficam em silêncio e o resultado aparece ao final das 12 tentativas.

Os resultados ficam no navegador, quando o armazenamento local está disponível. Use **Baixar resultados JSON** para exportá-los. O aplicativo não usa microfone nem envia resultados para servidores.

## Limitações

O desempenho também pode refletir memória da nota final, sem reconstrução mental de toda a frase. Uma pontuação maior não comprova melhora na composição ou transcrição. São apenas 12 respostas binárias por sessão, com chance de acerto de 50%; pequenas diferenças não demonstram aprendizagem.

Para avaliar transferência, grave uma frase que você criou mentalmente, escreva-a no MuseScore sem reprodução e só depois compare a partitura com a gravação. Observe a precisão das alturas e durações ao longo dos dias.

O arquivo HTML contém todo o código e o sintetizador de áudio, sem dependências externas.
