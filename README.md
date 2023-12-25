<div align="center">
    <img src="banners/42-light.png#gh-light-mode-only" alt="Banner (claro)" />
    <img src="banners/42-dark.png#gh-dark-mode-only" alt="Banner (oscuro)" />
    <br>
    <br>
    <a href='https://profile.intra.42.fr/users/antgalan' target="_blank">
        <img alt='42 (oscuro)' src='https://img.shields.io/badge/Málaga-black?style=flat&logo=42&logoColor=white'/>
    </a>
    <a href="https://wakatime.com/@srgalan">
        <img src="https://wakatime.com/badge/github/15Galan/42_project_readmes.svg" alt="Tiempo" />
    </a>
    <img src="https://img.shields.io/badge/idioma-🇪🇸-%23aaaaaa.svg?style=flat" alt="Idioma"/>
    <!-- <img src="https://api.visitorbadge.io/api/visitors?user=15Galan&repo=42_project_readmes&label=visitas&countColor=%2385e3ff&style=flat&labelStyle=none"/> -->
</div>

---

# READMEs para proyectos de 42

Este repositorio contiene elementos con los que decorar los READMEs de los proyectos de 42.

> [!IMPORTANT]
> No es necesario descargar ninguno de los elementos del repositorio para poder usarlos, ya que se pueden enlazar directamente usando sus URLs (utilizando Markdown o HTML) o bien se puede copiar y pegar el código fuente y modificarlo antes de usarlo.

> Puedes copiar un snippet de ejemplo [aquí](#snippet-de-ejemplo).

Adicionalmente, te explicaré cómo usar los elementos de este repositorio, lo que te permitirá entender mejor cómo funcionan los READMEs de GitHub y también, conocer algunos trucos para mejorar en la construcción de READMEs para tus proyectos personales, sean o no de 42.

## Elementos del repositorio

### Banners (encabezados)


Muestran el nombre del proyecto de una forma simple y elegante (temas claro y oscuro).

Estos son algunos ejemplos de cada tipo de banner:

<table>
    <thead>
        <tr>
            <th></th>
            <th>Tema claro</th>
            <th>Tema oscuro</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">Piscina</td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/piscine/exercises/c07-light.png">
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/piscine/exercises/c07-dark.png">
            </td>
        </tr>
        <tr>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/piscine/rushes/rush01-light.png">
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/piscine/rushes/rush01-dark.png">
            </td>
        </tr>
        <tr>
            <td rowspan="2">Cursus</td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/cursus/projects/libft-light.png">
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/cursus/projects/libft-dark.png">
            </td>
        </tr>
        <tr>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/cursus/exams/rank02-light.png">
                </td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/cursus/exams/rank02-dark.png">
            </td>
        </tr>
        <tr>
            <td rowspan="2">Evento</td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/events/cibersecurity-light.png">
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/events/cibersecurity-dark.png">
            </td>
        </tr>
    </tbody>
</table>

> [!NOTE]
> Observa que acabo de introducir imágenes en una tabla, y que además, esta tabla contiene celdas combinadas; esto es posible debido a que Markdown puede usar código HTML anidado, por lo que si observas el código fuente de este README, verás que la tabla está escrita en HTML.

#### Cómo usar un banner de este repositorio

1. Dirígete al banner que quieras usar.
2. <kbd>Clic derecho > Copiar dirección de la imagen</kbd>.

Verás que se ha copiado una URL en tu portapapeles con un formato similar a este:

```text
https://github.com/{usuario}/{repositorio}/blob/{rama}/{ruta-imagen}?raw=true
```

**Esta es la URL que puedes usar para enlazar la imagen con Markdown o HTML.**

> [!NOTE] Si copias y pegas la URL en el navegador, verás que se muestra la imagen en una página web. Esto quiere decir que la URL conduce a una imagen y por tanto, es lo que se obtendrá cuando se use en un README.

Adicionalmente, verás que la URL anterior habrá cambiado a una con este formato:

```text
https://raw.githubusercontent.com/{usuario}/{repositorio}/{rama}/{ruta-imagen}
```

Esta URL también es válida para enlazar la imagen, pero a diferencia de la anterior, esta URL pertenece a un **servicio de contenido estático** ofrecido por GitHub.

> [!NOTE]
> No importa qué formato de URL uses, ya que el primero redirige al segundo.


### Badges (insignias)

Muestran características del proyecto.

Estas insignias son genéricas y hay muchos servicios que las generan, siendo [Shield.io](https://shields.io/) el formato de insigina más popular y reconocido en el sector.

Ya que los READMEs a los que se hacen referencia en este repositorio son aquellos empleados para la visualización de proyectos de 42, se han incluido las siguientes insignias:

| Insignia | Servicio | Datos manuales |
| --- | --- | --- |
| El campus del estudiante | [Shield.io](https://shields.io) para la insignia.<br>[SimpleIcons](https://simpleicons.org) para el logo de 42. | El nombre del campus. |
| La puntuación del proyecto | [Shield.io](https://shields.io) para la insignia. | La puntuación final y la puntuación máxima. |
| El tiempo empleado en el proyecto | [Wakatime](https://wakatime.com) para la insignia. | La URL de la insignia, disponible en la plataforma. |
| Un contador de visitas | [Visitor Badge](https://visitor-badge.glitch.me) para la insignia. | El nombre de usuario y el repositorio de GitHub. |

> [!WARNING]
> Será necesario que tengas una cuenta activa en [Wakatime](https://wakatime.com) para poder usar su insignia en el proyecto. Una vez creada la cuenta, solo tienes que seguir estos pasos:
> 
> 1. Dirígete al proyecto en Wakatime.
> 2. Sincroniza el proyecto con tu repositorio de GitHub.
> 3. Copia la URL de la insignia.

#### Cómo usar una insignia de este repositorio

1. Dirígete a la insignia que quieras usar.
2. <kbd>Clic derecho > Copiar dirección de la imagen</kbd>.
3. Modifica el código fuente de la insignia según tus necesidades
    - Los campos modificables aparecen en la tabla anterior.

## Snippet de ejemplo

Este código puede copiarse y colocarse al inicio de cada README de un nuevo proyecto de 42.

```html
<div align="center">
    <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/cursus/libft-light.png#gh-light-mode-only" alt="Banner (claro)" />
    <img src="https://raw.githubusercontent.com/15Galan/42_project-readmes/master/banners/cursus/libft-dark.png#gh-dark-mode-only" alt="Banner (oscuro)" />
    <br>
    Texto sobre del proyecto; por ejemplo, un resumen de una línea, o incluso nada.
    <br>
    <a href='https://profile.intra.42.fr/users/antgalan' target="_blank">
        <img alt='42 (oscuro)' src='https://img.shields.io/badge/Málaga-black?style=flat&logo=42&logoColor=white'/>
    </a>
    <img src="https://img.shields.io/badge/puntuación-125%20%2F%20100-success?color=%2312bab9&style=flat" />
    <img src="https://wakatime.com/badge/github/15Galan/42_project_readmes.svg" alt="Tiempo" />
    <img src="https://api.visitorbadge.io/api/visitors?user=15Galan&repo=42_project_readmes&label=visitas&countColor=%2385e3ff&style=flat&labelStyle=none"/>
</div>

---

# Nombre del proyecto
```

Este fragmento de código contiene los siguientes elementos, centrados, y en este orden:

- 1 banner que cambia de color en función del tema de GitHub que use el lector.
- 4 insignias sobre el proyecto:
    - El campus del estudiante; este conduce al perfil de 42 del estudiante si se pulsa.
    - La puntuación del proyecto.
    - El tiempo empleado en el proyecto.
    - Un contador de visitas.

### Observaciones sobre el ejemplo

> [!WARNING]
> Este código es válido, pero contiene **mis datos**, por lo que tendrás que cambiarlos si pretendes usar este código en tu propio README.
> 
> Tu campus y nombre de usuario de 42 siempre serán los mismos, pero esto no se cumple para tu enlace de 42 del proyecto, ni tu enlace de Wakatime, ni el de las visitas del repositorio.

> [!IMPORTANT] Recuerda que puedes modificar el snippet según los procesos descritos en las secciones [Banners](#banners-encabezados) e [Insignias](#insignias-badges), permitiéndote **no tener que añadir ningún recurso multimedia en tu repositorio**.

**Cada banner tiene un atributo `#gh-light-mode-only` o `#gh-dark-mode-only`**  
Esto es lo que permitirá mostrar el banner de un color acorde al tema de GitHub que esté usando el usuario lector.

**Solo tendrás que cambiar los datos del snippet 1 vez / proyecto**  
Como la insignia de puntuación del proyecto es completamente manual, llega a crear una pequeña dependencia a terminar el proyecto para poder añadir un README que incluya la puntacuón del mismo; además, esto te evita problemas con las reglas de evaluación de 42.

No obstante, si eres una persona más experimentada con Git, te invito a que uses todas sus funcionalidades para poder sortear ese obstáculo (te puedo asegurar que es posible).