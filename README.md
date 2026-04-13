# Asignación de Discursos — Barrio Burgos

Aplicación web para la generación de cartas de asignación de discursos para la reunión sacramental del **Barrio Burgos** de la Iglesia de Jesucristo de los Santos de los Últimos Días.

## Funcionalidades

- Selección de título (Hermano / Hermana)
- Campo de nombre completo del orador
- Elección de duración del mensaje (5, 10, 15 o 20 minutos)
- Campo de tema del discurso
- Selección de fecha de la reunión
- Generación automática de carta formal con mensaje espiritual incluido
- Botón para **copiar** el texto de la carta
- Botón para **imprimir** directamente desde el navegador
- **Historial** de cartas generadas (guardado en `localStorage`)
- Diseño en colores azul y blanco, con tipografía elegante

## Uso

No requiere instalación ni dependencias. Es un archivo HTML estático.

### Opción 1 — Abrir localmente

1. Descarga el archivo `index.html`
2. Ábrelo directamente en cualquier navegador moderno

### Opción 2 — GitHub Pages

1. Sube este repositorio a GitHub
2. Ve a **Settings → Pages**
3. En *Branch*, selecciona `main` y carpeta `/ (root)`
4. Guarda los cambios
5. La app estará disponible en: `https://<tu-usuario>.github.io/<nombre-repositorio>/`

## Estructura del proyecto

```
/
└── index.html      # Aplicación completa (HTML + CSS + JS en un solo archivo)
└── README.md       # Este archivo
```

## Tecnologías

- HTML5, CSS3, JavaScript puro (sin frameworks ni dependencias externas)
- Fuentes: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) y [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3) vía Google Fonts
- Almacenamiento local con `localStorage`

## Vista previa

La carta generada incluye:

- Encabezado con nombre del barrio e institución
- Saludo personalizado según el título seleccionado
- Tema del discurso destacado visualmente
- Duración asignada
- Mensaje espiritual: *"El Señor le guiará en su esfuerzo por enseñar a sus hermanos la doctrina del evangelio y las enseñanzas del Salvador."*
- Firma del Obispado del Barrio Burgos

---

Desarrollado para uso interno del Barrio Burgos.
