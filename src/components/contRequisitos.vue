<template>
  <div id="divLista">
    <h2 id="tiList">Requisitos</h2>
    <div id="parLista" class="mb-5">
      <p class="parrafoList">
        La instrumentación acelerométrica a instalarse en edificios, deben
        cumplir requisitos mínimos para logar el óptimo monitoreo
        suelo-estructura.
      </p>
      <p class="parrafoList mt-5">
        A continuación, usted tiene a disposición el siguiente documento técnico
        que describe las "Especificaciones técnicas para regustradores
        acelerométricos y requisitos mínimos para su instalación, operación y
        mantenimiento Norma E.030 Diseño Sismo-resistente."
      </p>
    </div>
    <a id="btnAceldat" href="https://www.igp.gob.pe/servicios/aceldat-peru/images/especificaciones_tecnicas_para_instalacion_de_registradores_acelerometricos.pdf" target="_blank">
      <svg
        version="1.1"
        id="Layer_1"
        xmlns:sketch="http://www.bohemiancoding.com/sketch/ns"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        width="40px"
        height="40px"
        viewBox="0 0 49 64"
        enable-background="new 0 0 49 64"
        xml:space="preserve"
        fill=" #00132E"
        transform="matrix(-1, 0, 0, 1, 0, 0)"
        style="margin-right: 10px;"
      >
        <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
        <g
          id="SVGRepo_tracerCarrier"
          stroke-linecap="round"
          stroke-linejoin="round"
        ></g>
        <g id="SVGRepo_iconCarrier">
          <title>Document</title>
          <desc>Created with Sketch.</desc>
          <g id="Page-1" sketch:type="MSPage">
            <g
              id="Document"
              transform="translate(1.000000, 1.000000)"
              sketch:type="MSLayerGroup"
            >
              <path
                id="Shape_1_"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M47,18.1V60c0,1.1-0.9,2-2,2H2 c-1.1,0-2-0.9-2-2V2c0-1.1,0.9-2,2-2h25.9L47,18.1L47,18.1z"
              ></path>
              <path
                id="Shape"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M47,18.9H30c-1.1,0-2-0.9-2-2V1"
              ></path>
              <path
                id="Shape_2_"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M9,17h13"
              ></path>
              <path
                id="Shape_3_"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M9,27h31"
              ></path>
              <path
                id="Shape_4_"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M9,34h31"
              ></path>
              <path
                id="Shape_5_"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M9,43h31"
              ></path>
              <path
                id="Shape_6_"
                sketch:type="MSShapeGroup"
                fill="none"
                stroke=" #00132E"
                stroke-width="2"
                d="M9,49h31"
              ></path>
            </g>
          </g>
        </g>
      </svg>
      Ver Especificaciones Técnicas y requisitos mínimos
    </a>
    <br>
    <a id="btnAcercadeA" class="my-linktop" @click="recepGeo">Ver Acerca de</a>
  </div>
</template>
  
<script>
export default {
  methods: {
    recepGeo() {
      // Lógica de la función receptora
      document.querySelectorAll("#acerca").forEach((boton) => boton.click());
    },
  },
};
</script>
<style>
#divLista {
  margin: 0px 60px 0px 45px;
}
#tiList {
  font-style: normal;
  font-size: 20px;
  line-height: 26px;
  color: #0000Af;
  margin: 45px 0px 12px 0px;
}
#parLista {
  margin-bottom: 30px !important;
}
#btnAceldat {
  display: flex;
  text-align: left;
  align-items: center;
  justify-content: flex-start !important;
  padding: 12px 24px;
  border: 2px solid white;
  border-radius: 4px;
  background-color: white;
  color: #00132e;
  font-size: 16px;
  font-weight: 400;
  text-decoration: none;
  cursor: pointer;
}
#btnAceldat:hover {
  background-color: rgb(224, 224, 224);
  text-decoration: underline;
}
.parrafoList {
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  color: #00132e;
}

.select-css {
  display: block;
  font-size: 14px;
  font-weight: 400;
  color: #444;
  line-height: 1.3;
  padding: 0.4em 1.4em 0.3em 0.8em;
  width: 250px;
  max-width: 100%;
  box-sizing: border-box;
  margin: 15px 0px;
  border: 1px solid #aaa;
  box-shadow: 0 1px 0 1px rgba(0, 0, 0, 0.03);
  -moz-appearance: none;
  -webkit-appearance: none;
  appearance: none;
  background-color: #fff;
  background-image: url("data:image/svg+xml;charset=US-ASCII,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%22292.4%22%20height%3D%22292.4%22%3E%3Cpath%20fill%3D%22%23007CB2%22%20d%3D%22M287%2069.4a17.6%2017.6%200%200%200-13-5.4H18.4c-5%200-9.3%201.8-12.9%205.4A17.6%2017.6%200%200%200%200%2082.2c0%205%201.8%209.3%205.4%2012.9l128%20127.9c3.6%203.6%207.8%205.4%2012.8%205.4s9.2-1.8%2012.8-5.4L287%2095c3.5-3.5%205.4-7.8%205.4-12.8%200-5-1.9-9.2-5.5-12.8z%22%2F%3E%3C%2Fsvg%3E"),
    linear-gradient(to bottom, #ffffff 0%, #f7f7f7 100%);
  background-repeat: no-repeat, repeat;
  background-position: right 0.7em top 50%, 0 0;
  background-size: 0.65em auto, 100%;
}
.select-css::-ms-expand {
  display: none;
}
.select-css:hover {
  border-color: #888;
}
.select-css:focus {
  border-color: #aaa;
  box-shadow: 0 0 1px 3px rgba(59, 153, 252, 0.7);
  box-shadow: 0 0 0 3px -moz-mac-focusring;
  color: #222;
  outline: none;
}
.select-css option {
  font-weight: normal;
}

.table-container {
  margin-top: 20px;
}
.table {
  width: 350px;
}

th,
td {
  font-weight: 500;
}

a {
  color: #0000af;
  text-decoration: none;
  cursor: pointer;
}


#btnAcercadeA {
  width: 195px;
  height: 41px;
  background: #ffffff;
  border: 1px solid #0000Af;
  color: #0000Af;
  border-radius: 4.26437px;
  cursor: pointer;
  font-weight: 500;
  font-size: 14px;
  line-height: 15px;
  display: flex;
  align-items: center;
  justify-content: center;
}
#btnAcercadeA:hover {
  background-color: #0000af;
  color: #ffffff;
}
</style>
  