# Decisiones Técnicas

* **Fecha:** 2026-06-17
* **Decisión:** Usar HTML, CSS y JavaScript puros con TailwindCSS vía CDN en lugar de Vite/React.
* **Por qué:** Detecté que tu computadora no tiene instalado Node.js (necesario para Vite/React). Siguiendo tu regla de "Cero configuración" y "Simplicidad primero", esta opción me permite darte un prototipo que puedes abrir con doble clic sin tener que instalar absolutamente nada.
* **Impacto para ti:** Podrás abrir el archivo `index.html` directamente en tu navegador y todo funcionará al instante. El código será un poco más artesanal pero el resultado visual será el mismo.

---

* **Fecha:** 2026-06-17
* **Decisión:** Simulación de integraciones (Drive, Correo, WhatsApp).
* **Por qué:** Conectar APIs reales requiere configuraciones de cuentas de desarrollador y tokens que harían la prueba muy lenta.
* **Impacto para ti:** Verás botones que simulan la acción y cargan datos de prueba para que evalúes si el flujo tiene sentido antes de programar la conexión real.

---

* **Fecha:** 2026-06-17
* **Decisión:** Almacenamiento local (LocalStorage).
* **Por qué:** Es la forma más rápida de guardar datos sin configurar bases de datos.
* **Impacto para ti:** Los documentos y citas que crees se quedarán guardados en tu navegador. Si lo abres en modo incógnito o en otro equipo, no los verás.
