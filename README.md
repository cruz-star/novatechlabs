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
  - **Envío Real de Correo y Solicitudes:**
    - Al enviar el formulario de contacto o solicitud de activación, el sistema transmite la información vía HTTP al correo `novatechlabs0001@gmail.com` sin requerir que el cliente tenga un programa de correo configurado.
    - Se abre un modal interactivo con opciones inmediatas con 1 clic:
      * 🔴 **Abrir en Gmail Web:** Redacta y abre directamente en Gmail en una nueva pestaña.
      * 🟢 **Enviar por WhatsApp al Creador:** Genera el mensaje para enviarlo directamente al chat.
      * 📬 **Abrir en Programa de Correo (Outlook / Mail).**
      * 📋 **Copiar Mensaje Completo al Portapapeles.**
    - Además, **registra la solicitud instantáneamente en la bandeja del creador** para que nunca se pierda un cliente.

### 2. Consola del Creador (`admin.html` o Acceso Secreto en `index.html`)
El creador tiene dos formas cómodas y secretas de acceder al panel:

1. **Vía URL directa (Recomendada):**  
   Guardá en tus marcadores privados:  
   `https://cruz-star.github.io/novatechlabs/admin.html`
2. **Vía atajos secretos en el sitio de clientes (`index.html`):**  
   - **4 clics seguidos en el logotipo** de *novatechlabs* (arriba a la izquierda).
   - **Atajo de teclado:** Presionar `Ctrl + Shift + A` (o `Alt + A`) en cualquier momento.
   - **Parámetro secreto en la URL:** Entrar a `index.html?admin`.

#### 🔔 Sistema de Alertas de Pedidos y Solicitudes Recibidas:
- **Alerta Visual Inmediata:** Si un cliente solicita un instalador o activación, aparece un banner animado de alta visibilidad:  
  *«🔔 ¡NUEVA SOLICITUD DE CLIENTE REGISTRADA! Tenés X solicitudes pendientes de atención.»*
- **Alerta Sonora (Chime):** Emite un sonido suave cuando entra un nuevo pedido mientras el panel está abierto.
- **Bandeja de Solicitudes y Clientes (Inbox de Leads):**
  - Lista cronológica con Fecha y Hora, Nombre/Comercio, Producto solicitado, Tipo de solicitud, Teléfono/WhatsApp y Mensaje completo.
  - Botón directo para **responder por WhatsApp** con saludo prearmado.
  - Botón directo para **responder por Correo**.
  - Interruptor para cambiar estado entre `🟡 Pendiente` y `🟢 Atendido`.
  - Exportación de solicitudes a `.JSON`.

#### Control Total del Catálogo:
- **Protección con PIN:** PIN inicial por defecto: **`1234`**.
- **Cambiar mi PIN:** Modificá tu código PIN en cualquier momento desde el botón *"Cambiar PIN"*.
- **Agregar / Editar / Borrar proyectos:** Control absoluto sobre software, enlaces de descarga y características.
- **Exportar e Importar JSON:** Respaldo completo del catálogo.

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

## 📌 Publicación en GitHub Pages
1. Ir a **Settings** en el repositorio `cruz-star/novatechlabs`.
2. En la sección **Pages**, seleccionar **Deploy from a branch** (`main` / `root`).
3. El sitio público para tus clientes estará disponible en:  
   `https://cruz-star.github.io/novatechlabs/`
4. Tu consola privada de administración estará en:  
   `https://cruz-star.github.io/novatechlabs/admin.html`
