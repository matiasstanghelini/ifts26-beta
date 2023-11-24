<template>
  <div>
    <index></index>
    <div>
      <h1 class="text-center mt-5">Preinscripción</h1>
    </div>
    <div class="container mt-5">
      <ul class="list-steps list-steps-lg">
        <h2 class="text-left">Ingresos {{ currentYear + 1 }}</h2>
        <p>
          Para inscribirse en el primer cuatrimestre de {{ currentYear + 1 }}, a
          través del sistema SIU Guaraní, siga estos pasos:
        </p>
        <li class="list-steps-item">
          <h4>Paso 1</h4>
          <p>
            A partir del 30/10/2023 y hasta el 1/3/2024, se realizará la
            pre-inscripción al primer cuatrimestre del ciclo lectivo 2024
            mediante el sistema SIU Guaraní, podrá ingresar al siguiente enlace
            para iniciar su proceso de preinscripción:

            <a
              href="https://guarani-autogestionagencia.bue.edu.ar/preinscripcion/SSAALV/acceso"
              target="_blank"
              rel="noopener noreferrer">
              https://guarani-autogestionagencia.bue.edu.ar/preinscripcion/SSAALV/acceso
            </a>
            Es necesario crear un usuario y contraseña y seleccionar nuestro
            instituto, IFTS N° 26.
          </p>
        </li>
        <li class="list-steps-item">
          <h4>Paso 2</h4>
          <p>
            Para poder inscribirse, se requiere contar con un título secundario
            o constancia de título en trámite/finalización de estudios
            secundarios, otorgada por la autoridad del establecimiento. En caso
            de poseer un título secundario obtenido en el extranjero, se deberá
            convalidar el título si se desea realizar estudios de nivel superior
            en una institución nacional. Para solicitar la hoja de
            convalidación, se puede acceder al siguiente enlace:
            <a
              href="https://www.argentina.gob.ar/educacion/tramites/convalidar-titulo-secundario-de-paises-con-convenio"
              target="_blank"
              rel="noopener noreferrer">
              https://www.argentina.gob.ar/educacion/tramites/convalidar-titulo-secundario-de-paises-con-convenio
            </a>
          </p>
        </li>
        <li class="list-steps-item">
          <h4>Paso 3</h4>
          <p>
            Una vez que haya realizado la pre-inscripción por el SIU Guaraní, es
            necesario enviar por correo electrónico la documentación requerida
            (comprobante de pre-inscripción, título secundario y DNI - cada
            documento con frente y dorso) a las siguientes direcciones:
            <a href="mailto:tecnicaturaenseguridadehigiene@yahoo.com.ar"
              >tecnicaturaenseguridadehigiene@yahoo.com.ar</a
            >
            y
            <a href="mailto:tecnicaturagir@yahoo.com"
              >tecnicaturagir@yahoo.com</a
            >
            según corresponda. En el cuerpo del correo, se debe consignar la
            siguiente información:
          </p>
          <ul>
            <li>Apellido/s y Nombre/s:</li>
            <li>DNI:</li>
            <li>Tel:</li>
            <li>Carrera a la que se inscribe:</li>
            <li>
              Comprobante de preinscripción online donde figure el código (Ver
              paso 5)
            </li>
          </ul>
        </li>

        <li class="list-steps-item">
          <h4>Paso 4</h4>
          <p>
            Revise la imagen que se muestra (abajo de este instructivo) para ver
            el procedimiento completo a seguir para obtener el comprobante y
            envíenos el comprobante generado.
          </p>
        </li>

        <li class="list-steps-item mb-5">
          <h4>Paso 5</h4>
          <p>
            Espere a que le envíen el link para el curso de pre-ingreso del
            GCBA. Realice por último los exámenes de preingreso.
          </p>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import index from "~/pages/index.vue";
export default {
  name: "Preinscripción",
  components: {
    index,
  },
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>
