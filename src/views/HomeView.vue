<template>
    <a-scene>
      <a-sphere position="0 1.25 -5" radius="1.25" color="red"></a-sphere>
      <a-box ciccia position="-1 0.5 -3" rotation="0 45 0" width="1" height="1" depth="1" color="blue"></a-box>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="1000" height="1000" color="green"></a-plane>
      <a-sky color="#87CEEB"></a-sky>
      <a-camera look-controls wasd-controls cursor="rayOrigin: mouse"></a-camera>
      <a-entity laser-controls="hand: left" ></a-entity>
      <a-entity laser-controls="hand: right" ></a-entity>
      <a-light type="point" position="2 4 4" intensity="0.5"></a-light>
      <a-entity id="lightSphere" geometry ="primitive:sphere" material="color: white; shader:flat" light="type: point" position="-4 4 -10" animation="property: position; from: -4 3 -10; to: 4 3 -10; loop:true; dir:alternate;"></a-entity>
      
      <!-- modelli 3d -->
      <a-gltf-model src="/models/arcade-city/scene.gltf" position="350, 27, 171.4"></a-gltf-model>
      <a-gltf-model src="/models/house/scene.gltf" position="345, 0, 355"></a-gltf-model>
      <a-gltf-model src="/models/music-store/scene.gltf" position="-314, 0, 517.39"></a-gltf-model>
      <a-gltf-model src="/models/small-game-store/scene.gltf" position="-455, 0, 171.4"></a-gltf-model>
      <a-gltf-model src="/models/deployos_hermanos/scene.gltf" position="-217.8, 0, 1.64"></a-gltf-model>
      <a-gltf-model src="/models/city-park-at-sunset/scene.gltf" position="-347.6, 2.36, -326"></a-gltf-model>
      <a-gltf-model src="/models/medieval-fountain/scene.gltf" position="-347.6, 2.36, -326"></a-gltf-model>
    </a-scene>
  
</template>

<script>

</script>

