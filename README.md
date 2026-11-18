# ServiExpress

**Soluciones rápidas para tu hogar.**

ServiExpress es una aplicación móvil que conecta a las personas de Barranquilla con técnicos y trabajadores disponibles para servicios del hogar, de forma rápida y confiable. Este repositorio contiene la página web de presentación del proyecto.

## Sobre el proyecto

Muchas personas en Barranquilla quieren hacer un arreglo en casa y no conocen técnicos calificados. A veces alguien les recomienda a un trabajador y el trabajo queda mal hecho. ServiExpress actúa como intermediario entre el cliente y el técnico, y su principal ventaja son las **calificaciones**: antes de contratar, el cliente puede ver cómo ha sido valorado cada técnico y decidir con más confianza.

### Cómo funciona

1. **Elige el servicio** que necesitas desde el menú de la app.
2. **Indica dónde y cuándo**: dirección, fecha y hora, y confirma la solicitud.
3. **Recibe a tu técnico**: la app asigna uno y muestra su nombre y su teléfono de contacto.

### Servicios del prototipo

Limpieza de aire acondicionado, arreglos en casa, pintura, mudanza, limpieza de casa y reparación de refrigeración. Próximamente: albañilería, plomería y domicilios.

> **Sobre los precios:** ServiExpress conecta a las personas con los técnicos, pero no fija ni cobra los precios de los servicios. Cada técnico define el valor de su trabajo y lo acuerda directamente con el cliente.

## Qué incluye la página

- Anuncio principal en video (storytelling).
- Historia y origen del proyecto.
- Cómo funciona la app y servicios disponibles.
- Resumen del estudio de mercado (primera validación con un grupo inicial de personas).
- Presentación del equipo.
- Datos de contacto.

## Estructura del repositorio

```
.
├── index.html        # Página completa (HTML, CSS y JS en un solo archivo)
├── media/
│   ├── story.mp4     # Video del anuncio
│   ├── poster.jpg    # Imagen de portada del video
│   ├── logo.png      # Logo de ServiExpress
│   ├── app-fuera.jpg # Captura de la app: pantalla de inicio del celular
│   └── app-dentro.jpg# Captura de la app: servicios dentro de la app
└── README.md
```

La página no necesita instalación ni dependencias. Solo usa la fuente Google Fonts (Bricolage Grotesque e Inter), que se carga por internet.

## Cómo verla

**En tu computador:** descarga el repositorio y abre `index.html` en el navegador.

**En línea con GitHub Pages** (para compartir un enlace público):

1. Sube todo el contenido de esta carpeta a un repositorio de GitHub, con `index.html` en la raíz.
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la página estará disponible en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Equipo

| Integrante | Edad | Pasatiempo |
| --- | --- | --- |
| Ruth Becerra | 20 años | Todo lo relacionado con la peluquería |
| Luis Munera | 24 años | Resolver puzzles y problemas matemáticos |
| Andrés Valle | 20 años | Practicar calistenia |

Proyecto de la asignatura **Creación de Empresas**, Corporación Universitaria Americana, Barranquilla, Atlántico. Profesora: Milena Mantilla.

## Contacto

- Correo: contacto@serviexpress.co
- Teléfono: +57 300 000 0000

> Datos de ejemplo. Actualízalos en `index.html` (sección `#contacto`) cuando tengan los reales.

## Nota sobre el estudio de mercado

Los resultados del estudio son una primera validación hecha con un grupo inicial de personas cercanas, mediante un cuestionario de 15 preguntas en Microsoft Forms. Orientan las decisiones del producto y no representan a todo el mercado. El estudio se repetirá con más personas, de distintas edades y ciudades.
