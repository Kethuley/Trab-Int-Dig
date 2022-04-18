html>
<title>Nova Embalagem Roselanche</title>
<script src="https://aframe.io/releases/0.7.0/aframe.min.js"></script>
<script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js"></script>
<body style='margin : 0px; overflow: hidden;'>
  <a-scene embedded arjs>
    <!-- colocar aqui seu conteudo de AR -->
    <a-box position='0 0.5 0' material='color: white;' <a-image src="https://kethuley.github.io/Testear/freezer.jpg" position="-1 0 1"></a-image>
    <a-text position='0 2 0 'value="Dica"></a-text>
    <!-- na linha abaixo, a camera se move de acordo com o marcador -->
    <a-marker-camera preset='hiro'></a-marker-camera>
  </a-scene>
</body>
</html>
![freezer](https://user-images.githubusercontent.com/103197075/163870561-c8f4442e-bdf5-4f04-a57c-48fb52681529.jpg)
