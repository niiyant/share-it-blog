![blog-logo](https://github.com/user-attachments/assets/abe6f530-723e-4d4d-8924-2b6d40cd58c8)

# Share IT Blog 🚀

Bienvenido a **Share IT**. Somos una comunidad unida por el deseo de aprender, compartir conocimientos y crecer juntos en el ámbito tecnológico. Este es un rincón para intercambiar conocimientos y experiencias que nos han guiado y ayudado en nuestro recorrido.☀️

## 🛠️ Funcionalidades

- 📝 Publicación de artículos y recursos.
- 🏷️ Categorías y etiquetas para organizar el contenido.
- 🔍 Búsqueda de artículos y recursos.

## 💻 Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/share-it-blog.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd share-it-blog
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:

   ```bash
   npm start
   ```

5. Abre tu navegador y ve a `http://localhost:4321` para ver el blog en funcionamiento. 🌐

## 🤝 Contribuir

**Nota:** Para añadir nuevos artículos, debes ser parte de nuestra comunidad. Si deseas contribuir creando artículos en el futuro, por favor únete a nuestra comunidad. Ten en cuenta que también se revisará detalladamente el artículo antes de publicarlo😉

## 📄 Añadir Artículos y Recursos

Para añadir nuevos artículos y recursos al blog, sigue estos pasos:

1. Crea un nuevo archivo Markdown en el directorio `src/content/articles/` con la siguiente estructura:

   ```typescript
   ---
   title: 'Título del Artículo'
   description: 'Descripción corta del artículo'
   date: 'YYYY-MM-DD'
   draft: false
   author: 'Nombre del Autor'
   tags: 'etiqueta'
   ---
   Contenido del artículo en formato Markdown.

   ```

2. Guarda el archivo y el nuevo artículo aparecerá automáticamente en el blog. ✨

Para añadir nuevos recursos, crea un nuevo objeto en el archivo `src/utils/resources.ts` con las siguientes propiedades:

```typescript
interface Resource {
  title: string
  description: string
  slug: string
  date: Date
  category: string
}

export const resources: Resource[] = [
  {
    title: 'Nuevo Recurso',
    description: 'Descripción del nuevo recurso.',
    slug: 'URL del recurso',
    date: new Date('YYYY-MM-DD'),
    category: 'Categoría del recurso',
  },
]
```

## 👥 Añadir Autores

Para aparecer en la sección de Autores, añade tus datos dentro de los archivos Markdown de artículos (`src/content/articles/`). Asegúrate de incluir la información del autor en el siguiente formato:

```markdown
---
author:
  name: 'Nombre del Autor'
  avatar: 'URL del Avatar'
  role: 'Rol del Autor'
  github: 'URL de GitHub'
  linkedin: 'URL de LinkedIn'
  website: 'URL del porfolio web'
  about: 'Descripción corta del Autor'
---
```

**¡Gracias por visitar Share IT! 🙌**

## 🗂️ Estructura del Proyecto

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── content/
│   │   ├── articles/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
|       └── articles/
|       └── tags/
│       └── aboutUs.astro
│       └── collaborators.astro
│       └── collaborators.astro
|       └── resources.astro
└── package.json
```

## 🚀 Conoce al creador y el repositorio de la comunidad

- [Elias Velazquez 👨🏻‍💻](https://github.com/eliasvelazquezdev)
- [Share IT Recursos 📃](https://github.com/eliasvelazquezdev/share-it-resources)

---

Para aprender más sobre la estructura de carpetas de un proyecto Astro, consulta [guía sobre la estructura de proyectos en Astro](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acción                                                      |
| :------------------------ | :---------------------------------------------------------- |
| `npm install`             | Instala las dependencias                                    |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321`  |
| `npm run build`           | Construye tu sitio de producción en `./dist/`               |
| `npm run preview`         | Previsualiza tu construcción localmente, antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check`        |
| `npm run astro -- --help` | Obtén ayuda usando el CLI de Astro                          |

## 👀 ¿Quieres aprender más?

No dudes en consultar [Astro](https://docs.astro.build)
