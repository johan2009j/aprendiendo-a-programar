# Pet Nova

Sitio web de Pet Nova. Este repositorio contiene las páginas HTML exportadas del sitio original y una hoja de estilos CSS complementaria.

## Estructura

```text
pet-nova/
├── index.html
├── about-us.html
├── contact.html
├── functions.html
├── pet-nova-style.css
├── README.md
└── .gitignore
```

## Ver el sitio localmente

1. Descarga o clona este repositorio.
2. Abre `index.html` en un navegador.

También puedes usar la extensión **Live Server** de Visual Studio Code y seleccionar `index.html`.

## Publicar con GitHub Pages

1. Sube estos archivos a la rama principal (`main`) del repositorio.
2. En GitHub, entra en **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/ (root)`.
5. Guarda los cambios. GitHub generará el enlace del sitio.

## Notas importantes

- Las páginas HTML provienen de una exportación de Wix y conservan dependencias externas de la plataforma. Algunas funciones, recursos o componentes podrían seguir necesitando servicios de Wix y conexión a internet.
- Los enlaces de navegación hacia las páginas disponibles en este repositorio se ajustaron a rutas locales.
- El archivo `functions.html` se conserva con ese nombre porque no hay información suficiente para confirmar a qué ruta del sitio original corresponde.
- `pet-nova-style.css` es una hoja de estilos complementaria extraída del diseño. Se conserva separada y no se ha inyectado en las páginas exportadas, para evitar alterar el diseño original sin comprobar la correspondencia de sus clases.
- El menú o enlaces que apuntaban a páginas no incluidas en el archivo original (por ejemplo, Our Dogs o Privacy Policy) pueden seguir sin tener una página local equivalente.

## Tecnologías

- HTML
- CSS
- Recursos y componentes externos de Wix
