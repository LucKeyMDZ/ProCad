# ⚡ ProCad

**Programa libre y gratuito para diseñar esquemáticos y placas PCB, pensado para estudiantes de escuelas técnicas.**

ProCad nace en el aula: la idea es que un alumno que **nunca diseñó una placa** pueda empezar en minutos, pero que al terminar tenga en sus manos un diseño de **calidad profesional**.

---

## 🎯 ¿Para quién es?

- 👩‍🎓 **Estudiantes** que están dando sus primeros pasos en electrónica y diseño de PCB.
- 👨‍🏫 **Docentes** que buscan una herramienta simple, gratuita y sin instalaciones para usar en clase.
- 🔧 **Cualquier persona** que quiera aprender a pasar de un circuito a una placa real.

---

## ✨ ¿Qué puedo hacer con ProCad?

| Etapa | Qué hacés |
|---|---|
| 1️⃣ **Esquemático** | Dibujás tu circuito con componentes básicos (resistencias, LEDs, capacitores, etc.) y los conectás. |
| 2️⃣ **Placa PCB** | Pasás el circuito a la placa, ubicás los componentes y trazás las pistas. |
| 3️⃣ **Vista 3D** | Ves cómo va a quedar tu placa terminada antes de fabricarla. |

---

## 🚀 Cómo usarlo

### Opción 1 — Desde internet (lo más fácil)
Entrá a este enlace y empezá a diseñar:

👉 **[Abrir ProCad](https://procad-nine.vercel.app/)**

### Opción 2 — Sin internet
1. Descargá este repositorio con el botón verde **"<> Code" → "Download ZIP"**.
2. Descomprimí el archivo.
3. Hacé doble clic en **`index.html`**.

¡Listo! Se abre en tu navegador y funciona **sin conexión a internet** y **sin instalar nada**.

> 💡 Recomendado: usar Google Chrome, Microsoft Edge o Firefox actualizados.

---

## 💡 Principios del proyecto

- **Simple primero:** cada función tiene que poder usarla alguien que recién empieza.
- **Profesional al final:** lo simple no significa de juguete; el resultado tiene que servir para fabricar una placa real.
- **Libre y gratuito:** sin licencias, sin cuentas, sin pagos.
- **Funciona en cualquier compu:** un solo archivo, sin instalación y sin internet.

---

## 🆕 Novedades (27/10/2026)

- 🧷 **Las pistas ya no se despegan:** si movés o girás un componente de la placa, las pistas conectadas a sus pads ahora se acomodan solas para seguir pegadas (antes quedaban colgando en el lugar viejo).
- 🚧 **No se puede rutear fuera de la placa:** al dibujar una pista, si el próximo tramo se saldría del rectángulo verde, se bloquea y avisa (como ya pasaba con las esquinas a 90°).
- 🔩 **Agujeros de montaje:** nueva herramienta "Agujero" (tecla H) para marcar dónde va cada tornillo, en 4 diámetros (M2 a M5). No lleva cobre: es una guía para perforar después de grabar la placa.
- 🖼️ **Logos en el cobre:** subí una imagen y quedá lista para plancharla junto con las pistas — se convierte sola a blanco y negro, y se puede mover, girar y cambiar de tamaño.
- 📄 **Hoja del esquemático en A4 y descarga en PDF:** el esquemático ahora se dibuja en una hoja A4 apaisada con un rótulo abajo (proyecto, alumno, curso y el logo de la escuela), igual que en Proteus o KiCad. Se descarga en PDF, con un botón para centrar el circuito en la hoja y un aviso si algo queda afuera del margen.

### Novedades anteriores (20/10/2026)

- 🎨 **Estética renovada:** paleta de colores profesional (cobre y turquesa) en toda la interfaz.
- 🔩 **Orientación de las borneras:** ahora el símbolo y la huella de las borneras tienen una flechita/muesca que marca el lado por donde entran los cables (y se atornillan). Sirve para girarlas en la placa y que los tornillos queden accesibles desde afuera.
- 🚫 **No se solapan componentes en la placa:** al armar la placa (paso 2), ya no se puede arrastrar ni girar un componente hasta dejarlo montado arriba de otro, porque eso no se puede hacer en la vida real.
- 🏷️ **Etiquetas de red:** nuevo componente "Etiqueta de red" para el esquemático. Poniendo dos etiquetas con el mismo nombre en distintos puntos, el programa los da por conectados sin necesidad de dibujar el cable entre ellos (igual que ya pasaba con Positivo y Masa).
- 🔦 **Resaltado cruzado esquemático ↔ placa:** como en Proteus. Elegís un componente, un cable o una pista y tocás "Resaltar en la Placa" (o "Resaltar en el Esquemático") para encontrarlo al toque del otro lado.
- 📱 **Mejor en celular y tablet:** se ajustó el diseño para que la pantalla se acomode mejor, incluido el celular en horizontal.

---

## 🗺️ Estado del proyecto

ProCad está en etapa de **prototipo** 🧪. Ya se puede usar para practicar y se le van a ir agregando funciones nuevas a partir de las pruebas con alumnos.

¿Encontraste un error o tenés una idea? Contalo en la pestaña **[Issues](../../issues)** de este repositorio. ¡Toda devolución ayuda!

---

## 👤 Autor

Desarrollado por **mi**, docente y jefe de laboratorio en una escuela técnica de Mendoza, Argentina 🇦🇷, para que sus alumnos aprendan a diseñar placas con una herramienta propia.
