<template>
  <div class="reveal">
  <div class="slides">
    <section>
      <section>
        <h1>
          Desarrollo del alcance del sistema
        </h1>
      </section>
      <section>
        <p>
          Para el analisis de los límites de un sistema usualmente se tiene en cuenta el presupuesto, si el proyecto tiene uno.
        </p>
      </section>
      <section>
        <p>En este analisis los actores siempre están fuera del alcance del sistema que se conectan usando líneas de comunicación (límites) a los casos de uso.</p>
      </section>
      <section>
        <p>Al igual que muchas otras propiedades del proyecto, el alcance también puede cambiar con el tiempo y a medida que el analista aprende más sobre el proyecto.</p>
      </section>
    </section>
    <section>
      <section>
        <h1>Desarrollo de diagramas de casos de uso</h1>
      </section>
      <section>
        <p>El analisis de este diagrama se basa en un caso de uso principal que determina el flujo estandar de eventos en el sistema y posteriormente estan conectadas las rutas alternativas que definen variaciones sobre el comportamientos.</p>
      </section>
      <section>
        <p>Para el desarrollo de estos diagramas de caso se puede empezar usando un diagrama de flujos de datos a nivel de contexto y/o por obtener una lista de requerimientos que los usuarios esperan que cumpla el sistema, ya sea con entrevistas o sesiones guiadas y anotando los actores que estan involucrados en cada caso de uso y servicios que el caso de uso debera proveer.</p>
      </section>
      <section>
        <p>Para las fases iniciales del analisis se puede hacer uso de estos lineamientos:</p>
      </section>
      <section>
        <ul>
          <li>1) Identificar actores involucrados y especificaciones de negocios</li>
          <li>2) Identificar los eventos de alto nivel y describirlos con los casos de uso principales con la forma en la que estos lo inician.</li>
          <li>3) Revisar los casos de uso y  determinar las posibles variaciones del flujo de datos.</li>
        </ul>
        <p>Durante el analisis se podra establecer las rutas alternativas, ramificaciones y buscar actividades exitosas o fallidas dentro del caso de uso.</p>
      </section>
    </section>
    <section>
      <section>
        <h1>Desarrollo de escenarios de casos de uso</h1>
      </section>
      <section>
        <p>Cada caso de uso tiene una descripcion como escenario, como por ejemplo un ecenario de caso de uso seria describir lo que ocurre al registrar un producto ya existente.</p>
      </section>
      <section>
        <p>Los ecenarios de caso de uso no estan estandarizados, por lo que cada organización tiene sus maneras de realizarlo, sin embargo en los niveles de casos de uso se vera una plantilla para este analisis.</p>
      </section>
    </section>
    <section>
      <section>
        <h1>Niveles de los casos de uso</h1>
        <p>//TODO: Explicar tipos de desencadenadores</p>
      </section>
      <section>
        <p>Se puede crear casos de uso con varios niveles de menos a mas especifico utilizando un metodo definido por Alistair Cockburn, los niveles son:</p>
      </section>
      <section>
        <ul>
          <li>1- Blanco: es el nivel empresarial y define requisitos basicos</li>
          <li>2- Cometa:es el nivel de unidad de negocio o de departamento, es un resumen de los objetivos del sistema</li>
          <li>3- Azul: es el nivel de los objetivos de los usuarios</li>
          <li>4- Indigo: es el nivel funcional o subfuncional que definen mas a detalle el caso de uso</li>
          <li>5- Negro: es el nivel de subfuncion mas detallado y se toca lenguaje tecnico y la programacion.</li>
        </ul>
      </section>
      <section>
        <p>Algunas de las areas principales que podrian contener un ecenario de caso de uso serian:</p>
      </section>
      <section>
        <ul>
          <li>1- Encabezado que contiene identificadores e iniciadores del caso de uso: Orienta al lector y clasifica el caso de uso con nombre e ID unico, sigue con el area del sistema al que pertenece el caso de uso, luego los actores involucrados y una breve descripcion de lo que logra el caso de uso</li>
        </ul>
      </section>
      <section>
        <ul>
          <li>2- Los pasos realizados: Representa el flujo estandar de eventos y los pasos que se llevaron a cabo para completar con éxito el caso de uso, estos se enumeran con un numero entero (y con un numero entero si extienden otro evento) y pueden provenir de una entrevista detallada con los usuarios.</li>
        </ul>
      </section>
      <section>
        <ul>
          <li>3- Pie de pagina que contiene precondiciones, suposiciones, preguntas y demas informacion relacionada: Precondiciones o la condicion que requiere el caso de uso para poder llevarse a cabo, Postcondiciones o el estado del sistema despues de que termine el caso de uso (Resultados, mensajes a otros sistemas, etc.), suposiciones que definen los requisitos estipulados de la tecnologia requerida, garantia minima que declara lo minimo que se prometio a los usuarios y la garantia de éxito que es lo que satisfaceria a los usuarios.</li>
        </ul>
        </section>
    </section>
    <section>
      <section>
        <h1>Creacion de las descripciones de los casos de uso</h1>
      </section>
      <section>
        <p>Para crear las descripciones de casos de uso se pueden seguir estos pasos:</p>
      </section>
      <section>
        <ul>
          <li>1- Usar como punto de referencia historias agiles, los objetivos de la definicion del problema, la lista de requerimientos de los usuarios o una lista de caracteristicas.</li>
          <li>2- Preguntar sobre las tareas que se realizan para lograr la transaccion y si el caso de uso lee datos o actualiza tablas</li>
          <li>3- Averiguar si hay acciones que se pueden repetir</li>
          <li>4- El caso de uso finaliza cuando el usuario cumple con su objetivo</li>
        </ul>
      </section>
    </section>
    <section>
      <section>
        <h1>
          Por que son utiles los diagramas de casos de uso
        </h1>
      </section>
      <section>
        <p>Son utiles, ademas de que permiten mostrar el alcance, limites y requisitos del sistema, debido a que identifican a todos los actores en el dominio del problema para que el analista se pueda concentrar en las personas que usarian el sistema y enfocarse en extender sus capacidades y asegurar que disfruten su interaccion con su retroalimentacion.</p>
      </section>
      <section>
        <p>Ademas de poder identificar los procesos, mejora la comunicación con los integrantes de la organización al describir el sistema de manera grafica y en sintonia con la informacion que confieren los usuarios, que usualmente estan en formas de historias y en lenguaje natural.</p>
      </section>
      <section>
        <p>Debido a que siempre se documenta el evento desencadenador, el analista puede rastrear el flujo de eventos para escribir procesos logicos.</p>
      </section>
      <section>
        <p>Y finalmente ayuda a determinar si de debe crear o comprar el software que integrara el sistema.</p>
      </section>
    </section>
  </div>
    
  </div>


  </template>

<script setup>
import { onMounted } from 'vue';
import Reveal from 'reveal.js';
import Markdown from 'reveal.js/plugin/markdown/markdown.esm.js';

onMounted(() => {
  let deck = new Reveal({
    plugins: [Markdown],
  });
  deck.initialize();
});
</script>
