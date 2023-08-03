<template>
    <a-scene>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="1000" height="1000" color="green"></a-plane>
      <a-sky radius="1000"  color="#87CEEB"></a-sky>
      <a-camera look-controls wasd-controls cursor="rayOrigin: mouse" position="0 20 0"></a-camera>
      <a-entity laser-controls="hand: left" ></a-entity>
      <a-entity laser-controls="hand: right" ></a-entity>
      <a-light type="ambient" intensity="0.7" color="#eea500"></a-light>
      <a-light type="directional" color="#eea500" light="castShadow:true;" intensity="0.4" position="-5 3 1.5"></a-light>
    
      <!-- modelli 3d -->
      <a-gltf-model src="/models/house/scene.gltf" position="345, 0, 355" scale="0.35 0.35 0.35" rotation="0 180 0"></a-gltf-model>
      <a-gltf-model src="/models/music-store/scene.gltf" position="-314, 0, 517.39" scale="20 20 20" rotation=" 0 90 0"></a-gltf-model>
      <a-gltf-model src="/models/small-game-store/scene.gltf" position="-455, 0, 171.4" scale="0.6 0.6 0.6" rotation="0 -90 0"></a-gltf-model>
      <a-gltf-model src="/models/arcade-city/scene.gltf" position="350, 27, 171.4" scale="1.5 1.5 1.5" rotation="0 -90 0"></a-gltf-model>
      <a-gltf-model src="/models/deployos-hermanos/scene.gltf" position="-217.8, 0, 1.64" scale="15 15 15" rotation="0 -90 0"></a-gltf-model>
      <a-gltf-model src="/models/city-park-at-sunset/scene.gltf" position="-347.6, 2.36, -326" scale="5 5 5"></a-gltf-model>
      <a-gltf-model src="/models/medieval-fountain/scene.gltf" position="-347.6, 2.36, -326" scale="5 5 5"></a-gltf-model>
    </a-scene>
  
</template>

<script>

</script>

