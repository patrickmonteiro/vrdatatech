<template>
  <q-page class="container scene">
    <a-scene arjs='debugUIEnabled: false;'>
      <!-- <a-marker id='frac3' type='pattern' url='statics/marker/pt-frac3.patt' vidhandler>
        <a-entity geometry="primitive: circle; radius: 1" rotation="-90 0 0"
          scale="1.8 1.5 1.5" material="shader:gif;src:url(statics/india.gif);"
          gif=""></a-entity>
      </a-marker> -->
      <a-marker id='vid' type='pattern' url='statics/marker/pt-frac3.patt'>
            <a-plane src="statics/logoDataTech.png" scale="3.3 3.3 3.3" rotation="-90 0 0" position="0 0 0">
            </a-plane>

            <!-- <a-plane color="white" width="5" position="0 0 0" rotation="-90 0 0"></a-plane>
            <a-text value="Obra: Quadrado Magico Antonio Peticov" align="center" color="black" width="5"
                position="0 0.8 -1" rotation="-90 0 0"></a-text> -->
      </a-marker>
      <a-entity camera></a-entity>
    </a-scene>

  </q-page>
</template>

<script>
export default {
  name: 'Aframe'
}
</script>

<style>
.scene {
    z-index: 100 !important;
}
</style>
