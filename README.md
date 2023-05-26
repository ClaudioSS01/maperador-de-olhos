# maperador-de-olhos
<h1><a href="https://claudioss01.github.io/maperador-de-olhos/" target="_blank">Mapeador de Olhos</a></h1>

<p>O projeto "Mapeador de Olhos" é uma aplicação que utiliza técnicas de processamento de imagens e detecção de olhar para identificar a direção para a qual uma pessoa está olhando. Através da câmera do dispositivo, o código captura o vídeo em tempo real e realiza a detecção da direção do olhar com base em imagens de referência previamente treinadas.</p>

<p>O funcionamento do projeto é dividido em três etapas principais:</p>

<ol>
  <li><strong>Treinamento:</strong>
    <ul>
      <li>O usuário pode treinar o sistema para reconhecer diferentes direções do olhar. São disponibilizados seis botões para escolher as direções desejadas.</li>
      <li>Ao clicar em um dos botões, a imagem capturada pela câmera é processada e convertida em escala de cinza.</li>
      <li>Essa imagem processada é então armazenada como referência para a direção escolhida.</li>
    </ul>
  </li>
  <li><strong>Detecção:</strong>
    <ul>
      <li>Após o treinamento, o sistema inicia o processo de detecção do olhar.</li>
      <li>A cada 5 segundos, o código captura o frame atual do vídeo e o converte em escala de cinza.</li>
      <li>Em seguida, compara a imagem atual com as imagens de referência previamente treinadas.</li>
      <li>Calcula-se a diferença média de pixels entre as imagens e determina a direção do olhar com base na menor diferença encontrada.</li>
    </ul>
  </li>
  <li><strong>Resultado:</strong>
    <ul>
      <li>O resultado da detecção do olhar é exibido na tela, indicando a direção identificada.</li>
      <li>Além disso, o código utiliza síntese de voz para falar o valor correspondente à direção detectada.</li>
    </ul>
  </li>
</ol>

<p>Esse projeto oferece flexibilidade ao permitir que o usuário treine o sistema para reconhecer direções personalizadas, como olhar para cima, para baixo, para a esquerda, para a direita, entre outras. O código utiliza o processamento de imagens e cálculos de diferença para realizar a detecção de olhar em tempo real.</p>

<p>Para utilizar o projeto, basta incluir o código fornecido em um ambiente de desenvolvimento web compatível com HTML, CSS e JavaScript, e acessar a página resultante para interagir com os botões e iniciar a detecção do olhar.</p>

<p><em>Aviso: Este projeto é um exemplo didático e pode requerer ajustes e melhorias para ser aplicado em situações reais.</em></p>
