# Rueda Libre 🚲

Sitio web de **Rueda Libre**, un emprendimiento de Medellín que alquila bicicletas y organiza recorridos guiados por la ciudad. Es el proyecto trabajado durante el curso, construido con **Bootstrap 5.3** para demostrar el uso de componentes y de un diseño responsivo.

🔗 **Sitio publicado:** https://tomas497.github.io/rueda-libre/
📁 **Repositorio:** https://github.com/Tomas497/rueda-libre

## Páginas

| Página | Archivo | Contenido |
|---|---|---|
| Inicio | `index.html` | Portada, carrusel de promociones, servicios, flota, rutas, beneficios y cómo alquilar |
| Tarifas y rutas | `paginas/tarifas.html` | Tablas de precios de alquiler y de recorridos guiados |
| Reservas | `paginas/reservas.html` | Formulario de reserva con validación, modal de políticas y horario |
| Catálogo | `catalogo-bootstrap.html` | Ejercicio de grid y cards con la flota de bicicletas |

## Componentes de Bootstrap utilizados

| Componente / concepto | Dónde se usa |
|---|---|
| **Navbar colapsable** (`navbar-expand-lg`, `navbar-toggler`) | Menú en todas las páginas; se convierte en botón de hamburguesa en pantallas pequeñas |
| **Grid** (`container`, `row`, `col-*`, `g-*`) | Portada, servicios, flota, rutas, beneficios, formulario y footer |
| **Cards** (`card`, `card-img-top`, `h-100`) | Servicios, flota (8 bicicletas) y rutas |
| **Carrusel** (`carousel`) | Promociones del mes en el inicio |
| **Formulario con validación** (`needs-validation`, `invalid-feedback`) | Reserva de bicicletas: texto, número, correo, fecha, radios, select y checkbox |
| **Modal** (`modal`) | Políticas de alquiler en la página de reservas |
| **Alertas** (`alert`, `alert-dismissible`) | Aviso del documento de identidad y confirmación de la reserva enviada |
| **Badge** (`badge`) | Etiqueta "Nuevo" en bicicletas eléctricas |
| **Botones** (`btn`, `btn-primary`, `btn-outline-primary`) | Llamados a la acción personalizados con la paleta de la marca |
| **Tablas responsive** (`table-responsive`) | Tarifas de alquiler y de recorridos |
| **Utilidades** (`d-flex`, `d-none d-md-block`, `ratio`, `object-fit-cover`, `sticky-top`) | Espaciado, alineación y visibilidad por tamaño de pantalla |
| **Bootstrap Icons** | Iconos del menú, beneficios y footer |

## Diseño responsive

El diseño se adapta con los breakpoints de Bootstrap:

- **Celular (< 576px):** una columna, menú colapsado, tarjetas apiladas.
- **Tablet (≥ 576px y ≥ 768px):** dos columnas en servicios, rutas y formulario.
- **Escritorio (≥ 992px):** menú expandido, flota en 3 y 4 columnas.

## Accesibilidad

- Enlace "Saltar al contenido" al inicio de cada página.
- Texto alternativo descriptivo en las imágenes.
- Etiquetas (`label`) asociadas a cada campo y mensajes de error claros.
- Estilos de foco visibles y jerarquía de encabezados ordenada.

## Estructura del proyecto

```
rueda-libre/
├── index.html
├── catalogo-bootstrap.html
├── paginas/
│   ├── tarifas.html
│   └── reservas.html
├── css/
│   └── estilos.css        # Paleta, tipografía y ajustes sobre Bootstrap
├── img/                   # Logo, fotos de bicicletas, rutas y promociones
├── bitacora.txt
└── README.md
```

## Cómo ejecutarlo

No requiere instalación. Bootstrap se carga desde CDN, por lo que se necesita conexión a internet.

1. Clona el repositorio: `git clone https://github.com/Tomas497/rueda-libre.git`
2. Abre `index.html` en el navegador (o usa la extensión *Live Server* de VS Code).

## Publicación

El sitio se publica con **GitHub Pages** desde la rama `main` (Settings → Pages → Deploy from a branch → `main` / root).

## Tecnologías

HTML5 · CSS3 · Bootstrap 5.3.3 · Bootstrap Icons 1.11.3 · JavaScript (validación del formulario) · Google Fonts (Montserrat y Open Sans)
