# novatechlabs • Software & App Studio

Panel central y catálogo de aplicaciones, software de escritorio, utilidades móviles y herramientas web desarrolladas por **novatechlabs**.

📧 **Correo Oficial:** `novatechlabs0001@gmail.com`  
🌐 **Portal de Clientes (Público):** `index.html`  
🔐 **Consola del Creador (Privada):** `admin.html` (o `index.html?admin`)

---

## 👥 Arquitectura Separada: Clientes vs. Creador

Para mantener la seriedad comercial y la privacidad de tu negocio, el sistema divide por completo la experiencia entre tus **clientes** y vos como **creador**:

### 1. Vista de Clientes (`index.html`)
- **100% limpia y orientada a la venta:** Los clientes **no ven ningún botón de administración**, ni formularios de edición, ni accesos que rompan la imagen profesional.
- **Enfoque en Pruebas y Activaciones:**
  - Cada software cuenta con botones directos: **"Descargar Prueba"** (o *"Probar Gratis"*) y **"Activar Licencia"**.
  - **Banner orientativo:** Explica claramente los 3 pasos: (1) Descargar el instalador, (2) Probar el sistema en su negocio, (3) Solicitar la activación permanente sin perder sus datos.
  - **Formulario de contacto inteligente:** Al pulsar en *"Activar Licencia"* o *"Ficha"*, se preselecciona el sistema consultado con asunto preparado para enviar a `novatechlabs0001@gmail.com`.
  - **Filtros rápidos y buscador en vivo:** Navegación fluida por categorías (*Software Escritorio*, *Apps Móviles*, *Herramientas Web*).

### 2. Consola del Creador (`admin.html` o Acceso Secreto en `index.html`)
El creador tiene dos formas cómodas y secretas de acceder al panel:

1. **Vía URL directa (Recomendada):**  
   Guardá en tus marcadores privados:  
   `https://cruz-star.github.io/novatechlabs/admin.html`
2. **Vía atajos secretos en el sitio de clientes (`index.html`):**  
   - **4 clics seguidos en el logotipo** de *novatechlabs* (arriba a la izquierda).
   - **Atajo de teclado:** Presionar `Ctrl + Shift + A` (o `Alt + A`) en cualquier momento.
   - **Parámetro secreto en la URL:** Entrar a `index.html?admin`.

#### Funcionalidades del Creador:
- **Protección con PIN:** PIN inicial por defecto: **`1234`**.
- **Cambiar mi PIN:** Podés cambiar tu código PIN en cualquier momento desde el botón *"Cambiar mi PIN"* (requiere ingresar el PIN actual y confirmación). El nuevo PIN queda guardado en tu navegador.
- **Agregar nuevos proyectos / apps:** Nombre, versión, categoría, plataforma, estado, link directo de descarga del instalador demo, descripción y características.
- **Modificar proyectos existentes:** Editá cualquier dato, precio o enlace sin tocar código.
- **Eliminar proyectos:** Quita del catálogo cualquier software que no desees mostrar.
- **Exportar e Importar en formato `.JSON`:** Descargá una copia del catálogo para respaldar o actualizar el archivo base del repositorio.

---

## 🌟 Proyecto Insignia: StockFacil Business (v3.0)

**Software de Gestión Comercial y Punto de Venta (Windows)** desarrollado específicamente para kioscos, almacenes, minimercados y comercios de atención ágil:

- **Base de datos 100% local en el equipo:** Privacidad total. Toda la información comercial, clientes y ventas reside en la PC o notebook del cliente. Funciona de manera autónoma sin internet.
- **Caja rápida con atajos de teclado:** Cobro ágil con lector de códigos de barras, atajos tácticos (`F2`, `Enter`, `F4`, `F8`), cálculo automático de vuelto y comprobantes de venta.
- **Cuenta Corriente Comercial avanzada:** Límite de crédito por cliente, entregas y pagos parciales, historial de movimientos y ajuste de saldo por precio actual.
- **Control de costos, márgenes y vencimientos:** Cálculo automático de márgenes de ganancia porcentuales, alertas de mercadería próxima a vencer y auditoría de inventario.
- **Aumento masivo de precios protegido por PIN:** Modificación rápida de precios por porcentaje general o por rubro con clave de seguridad para evitar errores humanos.
- **Arqueo de caja y seguridad:** Registro estricto de apertura y cierre de turnos, discriminación de gastos y retiros de dinero justificados, y generación de respaldos completos en formato `.JSON`.

---

## 🎨 Estética y Diseño (Dark Mode de Alto Contraste)
- **Fondo principal:** Negro absoluto (`#0B0B0D`).
- **Tarjetas y paneles:** `#141418` con bordes sutiles en `#2B2B33` y hover reactivo ámbar.
- **Barra lateral:** `#101014` fija en escritorio y drawer táctil en celulares.
- **Acentos y acciones destacadas:** Degradé amarillo-naranja cálido (`#FFB800` a `#FF6A00`) con tipografía en negrita oscura (`#09090B`).
- **Logotipo propio:** Emblema geométrico poligonal vectorizado inline en SVG con degradé ámbar.

---

## 📌 Publicación en GitHub Pages
1. Ir a **Settings** en el repositorio `cruz-star/novatechlabs`.
2. En la sección **Pages**, seleccionar **Deploy from a branch** (`main` / `root`).
3. El sitio público para tus clientes estará disponible en:  
   `https://cruz-star.github.io/novatechlabs/`
4. Tu consola privada de administración estará en:  
   `https://cruz-star.github.io/novatechlabs/admin.html`
