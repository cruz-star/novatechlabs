# novatechlabs • Software & App Studio

Panel central y catálogo de aplicaciones, software de escritorio, utilidades móviles y herramientas web desarrolladas por **novatechlabs**.

🌐 **Sitio Web / Dashboard:** Diseñado como un único archivo estático `index.html` sin dependencias externas, listo para GitHub Pages o cualquier servidor web.  
📧 **Correo Oficial:** `novatechlabs0001@gmail.com`

---

## 🌟 Proyecto Insignia: StockFacil Business (v3.0)

**Software de Gestión Comercial y Punto de Venta (Windows)** desarrollado específicamente para kioscos, almacenes, minimercados y comercios de atención ágil.

- **Base de datos 100% local en el equipo:** Privacidad total. Toda la información comercial, clientes y ventas reside en la PC o notebook del cliente. Funciona de manera autónoma sin internet.
- **Caja rápida con atajos de teclado:** Cobro ágil con lector de códigos de barras, atajos tácticos (`F2`, `Enter`, `F4`, `F8`), cálculo automático de vuelto y emisión de tickets de venta.
- **Cuenta Corriente Comercial avanzada:** Límite de crédito por cliente, entregas y pagos parciales, historial cronológico de movimientos y ajuste de saldo por precio actual.
- **Control de costos, márgenes y vencimientos:** Cálculo automático de márgenes de ganancia porcentuales, alertas de mercadería próxima a vencer y auditoría de inventario.
- **Aumento masivo de precios protegido por PIN:** Modificación rápida de precios por porcentaje general o por rubro con clave de seguridad para evitar errores humanos.
- **Arqueo de caja y seguridad:** Registro estricto de apertura y cierre de turnos, discriminación de gastos y retiros de dinero justificados, y generación de respaldos completos en formato `.JSON`.

---

## 🎨 Estética y Diseño (Dark Mode de Alto Contraste)

El dashboard fue construido siguiendo estrictas pautas de diseño para entornos de gestión modernos:
- **Fondo principal:** Negro absoluto (`#0B0B0D`) para reducir fatiga visual.
- **Tarjetas y paneles:** `#141418` con bordes sutiles en `#2B2B33` y hover reactivo con brillo ámbar.
- **Barra lateral:** `#101014` fija en escritorio y con navegación drawer en dispositivos móviles.
- **Acentos y acciones destacadas:** Degradé amarillo-naranja cálido (`#FFB800` a `#FF6A00`) con tipografía en negrita oscura (`#09090B`).
- **Tipografía:** Blanco puro (`#FFFFFF`) para títulos principales y gris neutro (`#A1A1AA` / `#71717A`) para textos secundarios y metadatos.
- **Logotipo propio con emblema geométrico:** Vector SVG puro integrado sin archivos externos.

---

## 🚀 Funcionalidades del Dashboard

### 1. Catálogo Dinámico y Buscador en Vivo
- **Filtros por categoría:** *Todos los Proyectos*, *Software Escritorio*, *Apps Móviles* y *Herramientas Web*.
- **Contadores sincronizados en tiempo real:** Muestran la cantidad exacta de proyectos disponibles en cada sección.
- **Búsqueda instantánea:** Filtra por nombre, plataforma o características con botón rápido de limpieza.
- **Ficha Técnica Detallada (Modal):** Permite explorar el propósito, entorno, requisitos, tipo de licencia y características completas de cada software.

### 2. Modo Administrador (Gestión del Catálogo)
- Protegido por PIN de seguridad (PIN por defecto: **`1234`**).
- Permite **agregar nuevas apps y software**, **editar proyectos existentes** y **eliminar** elementos que no se deseen mostrar.
- Los datos se preservan automáticamente en el navegador (`localStorage`).
- **Exportar Catálogo en .JSON:** Genera y descarga un archivo `.json` listo para respaldar o integrar en el código fuente.
- **Importar Catálogo desde .JSON:** Permite cargar catálogos previos de forma inmediata.
- **Restablecer catálogo inicial:** Botón de un solo clic para volver a los proyectos predeterminados del estudio.

### 3. Contacto y Canal de Mejoras
- **Copiado rápido de correo:** Un clic en `novatechlabs0001@gmail.com` copia la dirección al portapapeles con feedback visual en pantalla (Toast).
- **Formulario integrado con enlace `mailto:`:** Al seleccionar un proyecto (o pulsar *"Solicitar / Consultar"* desde una tarjeta), el formulario autocompleta el asunto y la plantilla de mensaje para enviar directamente al equipo de novatechlabs.

---

## 🛠️ Tecnologías Empleadas
- **HTML5 Semántico y Accesible.**
- **CSS3 Moderno:** Variables nativas (`CSS Custom Properties`), Flexbox, CSS Grid y efectos de transición suaves.
- **JavaScript Vanilla (ES6+):** Sin dependencias de librerías externas o CDNs que puedan fallar sin conexión.
- **Iconografía SVG optimizada inline:** Carga ultrarrápida (0 ms de latencia de red).

---

## 📌 Publicación en GitHub Pages
1. Ir a la pestaña **Settings** (Configuración) del repositorio en GitHub.
2. Acceder a la sección **Pages** (en el menú lateral izquierdo).
3. En **Build and deployment > Source**, seleccionar **Deploy from a branch**.
4. Seleccionar la rama `main` y la carpeta `/ (root)`.
5. Hacer clic en **Save**. En unos minutos el sitio estará activo en:
   `https://cruz-star.github.io/novatechlabs/`
