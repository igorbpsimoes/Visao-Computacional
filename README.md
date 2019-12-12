# Projeto de Rastreamento Planar
Segundo projeto da disciplina Processamento Gráfico(IF680) feito em dupla por Igor Beltrão Pereira Simões(ibps) e Victor Edmond Freire Gaudiot(vefg).

### Objetivo
Dada uma imagem de refência, identifica-lá no vídeo dado(tanto da webcam quanto vídeos normais) e destacá-la com um contorno colorido.

### Funcionamento
Apesar do código também funcionar para ORB, optamos utilizar o AKAZE como ferramenta de para detectar os pontos chaves e descritores da imagem/frame.

Para a realização do casamento de pontos entre os pontos chaves da imagem de referência e da imagem do vídeo, utilizamos a técnica de força bruta, onde comparavamos pontos chaves 2 a 2 e escolhíamos aquele que aparentava ser mais correto.

#### Observações:
Esse repositório contém apenas o main.cpp, para rodar o projeto, deve-se [baixar](http://google.com.br/) todos os arquivos e substituir o main.cpp do arquivo baixado pelo main.cpp deste repositório. De preferência compilar o projeto no Visual Studio.

A lib foi buildada e compilada pelo monitor Josue Fidelis de Oliveira Neto.
