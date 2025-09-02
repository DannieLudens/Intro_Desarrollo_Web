# Proyecto de curso: Portafolio

## Propuesta incial

### Nombre del proyecto: 

**Portafolio Web Personal**

**Por:** Daniel Esteban Ardila Alzate 

**Para la materia:** introducción al desarrollo web

**Dictada por:** Andrés Felipe Diaz González

### Objetivo general

Diseñar y desarrollar un sitio web personal que funcione como portafolio digital, donde pueda mostrar mis proyectos, habilidades, estudios y datos de contacto de manera atractiva, organizada y accesible desde cualquier dispositivo.

### Objetivos específicos

- Aplicar los conocimientos adquiridos en HTML para estructurar correctamente el contenido del sitio.
- Utilizar CSS para diseñar una interfaz visual atractiva, coherente y responsiva.
- Incluir elementos interactivos y multimedia mediante JavaScript, p5.js y etiquetas HTML, como botones, efectos visuales, formularios, integración de videos (YouTube y propios), audio, modelos 3D, GIFs, archivos descargables y sketches interactivos hechos con p5.js, que enriquezcan la experiencia del usuario.
- Crear secciones específicas para proyectos, habilidades, biografía, hoja de vida y contacto.
- Asegurar la correcta visualización del sitio tanto en computadoras como en dispositivos móviles

<img width="500" alt="image" src="https://github.com/user-attachments/assets/afd26d69-26d8-400c-8aa7-950df9db1171" />

## Diseño de Interfaz inicial UX/UI Figma

<details>
  <summary>User Flow y Wireframe</summary>
  
</details>

<details>
  <summary>Prototipo en Baja</summary>
  
</details>

<details>
  <summary>Prototipo en media: Diseño UX/UI inicial</summary>
  

- Para el Header hice esta propuesta visual inicial:

<img width="643"  alt="Figma_XdijqiGa6B" src="https://github.com/user-attachments/assets/2dbbae42-066c-439d-80de-13c952369c9b" />

- Como Homepage tengo pensado hacer un resumen general de que se v a aencontrar en el protafolio

<img width="643" alt="image" src="https://github.com/user-attachments/assets/afd26d69-26d8-400c-8aa7-950df9db1171" />

- Para la sección de Proyectos tengo pensado dos opciones sin embargo, tomare decisiones cuando lo pruebe
  
  - Opcion 1 de proyectos:

  <img width="643" alt="image" src="https://github.com/user-attachments/assets/2d1b8b28-562a-4f23-8dae-dee6f3ff3fc1" />

  - Opcion 2 de proyectos:

  <img width="643" alt="image" src="https://github.com/user-attachments/assets/9c4c1233-235b-4b80-acbc-1f9e86332ee6" />

- Para la seccion de contacto

<img width="643" alt="image" src="https://github.com/user-attachments/assets/afb05fd5-71f2-4933-9cb7-dcfeaf3ed125" />

- Para la seccion de tienda donde pienso tener un micro emprendimiento

<img width="643" alt="image" src="https://github.com/user-attachments/assets/5195c2f6-1d23-4c9e-afae-5f7711cbfadb" />

- Para la seccion de Hoja de Vida (CV) Pensaba poner en formato estandarizado para descargar o visualizar

<img width="643" alt="image" src="https://github.com/user-attachments/assets/670000c3-0143-44f7-a7cd-1c3fb664a913" />


</details>

<details>
<summary>Prototipo en Alta</summary>
  
</details>


## Primera Entrega esqueleto HTML

El primer encargo fue el de mostrar el esqueleto de la pagina propuesta sin estilos

### Estructura html

<details>
  <summary>Codigo html</summary>

portafolio.html
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Portafolio</title>
    <meta charset="UTF-8">
  </head>
  <body>
    <header>
      <h2>Portfolio</h2>
      <nav>
        <a href="#">Projects</a>
        <a href="#">Contact</a>
        <a href="#">CV</a>
        <a href="#">Merchandise</a>
      </nav>
      <form>
        <input placeholder="Search" value="" />
      </form>
    </header>
    <main>
      <section>
        <div>
          <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuCLkHk-MRRSQmHFrNt7MJIJ3BTSrtnL7RaKuf6Bh9pDlGhb1NmV30aV0P5elqRuRNCBzKhRxgWAxMyN_MCaUi6eO_SAfXOmamRkxf56g-kZADiMdRwfzcuEScjRcYmfP2Ai0acSMFudOSkR33qDSz4BysSO4LWjrgqP3pkGqmbL4zFKQTE6mtIo5QLa24kRue_qCO3d5Sl5B0fXCB13M4O7RFb_hh6BfhuZuJDzOjR_QBwRiwdLRbF_jZW5MwHpoAdHUA1aYHfBO-uC" alt="Banner" width="100%" />
        </div>
        <div>
          <img src="pp.png" alt="Foto de perfil" width="128" height="128" />
          <div>
            <p>Daniel Ardila</p>
            <p>Ingeniero en diseño de entretenimiento digital</p>
          </div>
        </div>
        <p>
          Soy un diseñador de productos con pasión por crear experiencias de usuario intuitivas y atractivas. 
          Me especializo en diseño de interfaz de usuario (UI) y experiencia de usuario (UX), 
          con un enfoque en la creación de productos digitales que sean tanto estéticos como funcionales. 
          Mi objetivo es resolver problemas complejos a través de la ingeniería y el diseño, asegurando que 
          cada interacción sea fluida y agradable.
        </p>
      </section>
      <section>
        <h2>Proyectos destacados</h2>
        <div>
          <div>
            <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuA19eRBkAiEqiS1D9Hvi5VQd460fdpx6qQeIUoXpTlIjc3Mbr5QMwMiC5bBg21CxQQhQP_41zxPsGuaFOnU1guyjCrucYicOr8q_U8B0COlt2FtOi8Ku10071YnqsIUBk2VCq6XCHeu9rEBv-zsjgoe0ieQidNQOe6EI5SFNWYT6nywSadLzcHb_KQBEETXHbl0N8IL_-V3BnJG8IDnrDyjXAq901K6a2mzgk_HK-tbUdxS9g0DulQjrBVClfhzYeIP1-VbiEKhHNS6" alt="Website Redesign" width="200" height="112" />
            <p>Rediseño de sitio web</p>
            <p>Un rediseño completo del sitio web de una empresa para mejorar la participación del usuario y las tasas de conversión.</p>
          </div>
          <div>
            <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuAfBjZsv-w5Aq0gnrz5ChDG5FnOHx_BBnGG8uGzKlugJ50a4fFXkiaMcfdaxpPR1Lnac5WSqyaruO155NPV4jcK0ZUr7LOZAR5VLtoC1LVHVbFHSjMhtcJhkrh1bPOT4ep7CiLUPeQdRbDHb2lVwvLt-WGm5w0g9A_OeRtXcbLt12GbCGjr99poOF95CNuDS4ekYVrXU5WK5cI8MX89i4mIEE6pVlCa6f7gOYZZct0qlgNdQqeJlMOljWrlQWrFNADo7KGb2A6Av4it" alt="Mobile App Concept" width="200" height="112" />
            <p>Concepto de App movil</p>
            <p>Un diseño conceptual para una aplicación móvil destinada a simplificar las tareas diarias.</p>
          </div>
          <div>
            <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdRzZw_aG6_0YptxuXM7WTXYLJLH7SHzAq_p8WoVNG0copdbzqXXrUDFwEe0qHNFmSr8nGQIfZlauq-AbJUNxRzCyB3CRVuFwqFxteXfqNCCwRRIp_JBrASyw4as81HXLGmuxVw2yf9qoragnK4s4d1WjETZbLZmz2MaxbBcQNlCNmIQPATjUsFMGZVPa7jRDildlqcGh50myQb7F_v9WtiybVGMsZKefglawp_7_FdXqDiyebqRcFto7MGtMclQFwG7x8EwNN2p6t" alt="E-commerce Platform" width="200" height="112" />
            <p>Plataforma de comercio electrónico</p>
            <p>Diseño y desarrollo de una plataforma de comercio electrónico con un enfoque en la experiencia del usuario.</p>
          </div>
        </div>
      </section>
      <section>
        <h2>Clientes y Colaboradores</h2>
        <div>
          <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuC32RDUv980ozzkGlPR3vQ-EYBGSDW8M7JOqVRjP0VkHOldO0nM6j9HUWFEpWcOQ39EhIRzAqGTf8B_rPrqFvccFMGgosAiFErJlkoz_lrKywKaNOJj3om2pHBW3_Lxo9gry_k0BgTIKAwkNq6aO8wRK1uHnCFGubwzz6kT4EcfqLBVvZFj1bGz5i0E5NurFQZklDedkVjnGLTkWf8XT7J7FY_xvVGkddkGdQLzQBM303MA7N-E2n6pKY_fkN276N7iO1NLgyB-rn6Q" alt="Cliente 1" width="100" height="100" />
          <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuCiygdCW1Ajkwh9ma727RA6ln4OGrY1l6A2sO_S9QNLXt3pOBXx5JCVTbbEbXvqx8Gddqle6SkOaItAoU0CgIc-hiPYL52q0STR7ENJfO13uzBq_mOES0n_j38r3y6ocMsKvG6s3zW-VWEW3lztpzNRa7__kDIS-1Ql64zumI4mog04oyc4xldLchFocXEih6R26jdNuKx8OL_kROsk3Ejuu0H-q21W0SOb2U2WZmX4u2uy9sIHkuoDLazAbVYMBTtbty8Yn1lG7mdp" alt="Cliente 2" width="100" height="100" />
          <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuBj7yIflZjOJzOqPOfe6zZVoYxsHmRvJM5zdXUnc48y_We0o6s8nIHO_7omgV8AvHJici8xwgQd10UhvySDy0iP854XZrgeH-KwXWCc55omijr9H_wZmG27k5vw4kbvf0n3jaUncVtUK4V4dUGlaMfXpnfbO3RNvyIdHyrUjrMZ-dBGRM1d5g0-vYD7EFVZ-WC7V0vzUc7khKwNpIiQiBPryusZZH9DmdFRe2z5mhN2GqD1W9jtSXAnx5iB6JWtiQJooJw-AKaDATa0" alt="Cliente 3" width="100" height="100" />
          <img src="https://lh3.googleusercontent.com/aida-public/AB6AXuB3g0FhoMOpjzzbFLojrZ7ku4f8lyRDyp4kleu-bttrffFh2B5DsRD4Ik2_zKKioqDvqpYo_-qh9YV7B8cjX-x4KqFSerWWDrKC4FSZbckc0nF9n_Be_bNPRy4Wcmd56V-FIZOQxFIXZELmH0j6Ujaztw1NsVS_YjyF9Kkc4JQfpKLWT1MVFPNODVX4bLwacWPDG1aYa7WkS5uEc4_y5-7UwyPkKQRt5h6dY3lNwzDG-6mEpSySFr3_1uXigPirewDN5Jg4wsFbKRkA" alt="Cliente 4" width="100" height="100" />
        </div>
      </section>
      <section>
        <a href="#">Contáctame</a>
      </section>
    </main>
    <footer>
      <nav>
        <a href="#">Contacto</a>
        <a href="#">CV</a>
      </nav>
      <p>@2025 Daniel Ardila. Todos los derechos reservados.</p>
    </footer>
  </body>
</html>
```

</details>
