---
title: "Pristimantis zophus"
output: html_document
---

<style>
/* CSS para las pestañas */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}
.tab button:hover {
  background-color: #ddd;
}
.tab button.active {
  background-color: #ccc;
}
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>

## Pristimantis zophus

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'DescripcionC')">Descripción</button>
  <button class="tablinks" onclick="openTab(event, 'EspectrogramaC')">Espectrograma</button>
  <button class="tablinks" onclick="openTab(event, 'TablasC')">Tablas</button>
  <button class="tablinks" onclick="openTab(event, 'AudiosC')">Audios</button>
</div>

<div id="DescripcionC" class="tabcontent">
  <h3>Descripción</h3>
  <img src="/docs/images/MHUA-A8988_Pristimantis_zophus.JPG" alt="Pristimantis zophus" style="width:10cm;">

 <p>Si utiliza los datos, cítese como:</p>

  <p><strong>Marín, C.M., C. Molina-Zuluaga, A. Restrepo, E.Cano & J.M. Daza.</strong> 2018. A new species of <i>Leucostethus</i> (Anura: Dendrobatidae) from the eastern versant of the Central Cordillera of Colombia with comments on the phylogenetic position of <i>Colostethus fraterdanieli</i>. <i>Zootaxa</i> 4461: 359--380. <a href="https://doi.org/10.11646/zootaxa.4461.3.3">https://doi.org/10.11646/zootaxa.4461.3.3</a>.</p>
</div>

<div id="EspectrogramaC" class="tabcontent">
  <h3>Espectrograma</h3>
  <img src="Espectrograms/espectrograma1.png" alt="Espectrograma 1" style="width:100%;">
</div>

<div id="TablasC" class="tabcontent">
  <h3>Tablas</h3>
  <p>Tabla de medidas</p>
  <p>Tabla de seleccion (Raven)</p>
</div>

<div id="AudiosC" class="tabcontent">
  <h3>Audios</h3>
<div class="audio-container">
    <audio controls>
      <source src="Audios/JAGUAS259_20130118_125515.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
    <audio controls>
      <source src="Audios/JAGUAS259_20130118_125515.wav" type="audio/wav">
      Tu navegador no soporta el elemento de audio.
    </audio>
  </div>
</div>