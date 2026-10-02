# Test de Autoexploración BDSM & Dinámicas de Poder 🌹🖤

Un aplicativo web interactivo, introspectivo y educativo diseñado para ayudar a las personas a explorar sus inclinaciones en dinámicas de poder, prácticas BDSM y gestión de límites mediante el marco de consentimiento informado (**SSC / RACK**).

A través de un cuestionario dinámico de 100 preguntas organizadas por categorías, la herramienta genera un perfil detallado del usuario, categoriza sus límites y ofrece un informe final exportable en PDF con diseño profesional y sensual.

---

## 🎨 Estética & Diseño

El proyecto cuenta con una interfaz oscura (*Dark Mode*) sofisticada y elegante que combina tonos intensos y acentos suaves:

* **Fondo Principal:** Negro Azabache (`#0D0D0D`) / Gris Carbón (`#121212`)
* **Color Primario:** Rojo Borgoña / Vino (`#8B0000` / `#6B0F1A`)
* **Color Secundario & Acentos:** Rosa Cuarzo / Neón Suave (`#E8A5C8` / `#FF2A6D`)
* **Tipografía:** *Playfair Display* (Títulos) y *Montserrat* o *Poppins* (Cuerpo)

---

## ✨ Características Principales

* **Cuestionario Adaptativo de 80 Preguntas:**
* **Evaluación Inicial:** Las primeras 15 preguntas determinan la inclinación dominante, sumisa o *switch*.
* **Lógica de Ramificación:** Ajusta y prioriza las preguntas posteriores según la tendencia detectada.


* **Escala Likert de 5 Puntos:**
* `0` — *Hard Limit* (Rechazo absoluto)
* `1` — *Soft Limit* (Poco interés / Solo en contextos específicos)
* `2` — Curiosidad / Neutral
* `3` — Disfruto moderadamente
* `4` — Deseo clave / Esencial para mí


* **Desglose por Categorías:**
* Dominación & Sumisión (D/s)
* Bondage & Restricción
* Sensorial, Sadismo & Masoquismo
* Roles & Dinámicas Psicológicas
* Cuidado, Servicio & Protocolo
* Seguridad, Comunicación & Consentimiento


* **Resultados e Informe Final:**
* Gráfico de perfil por porcentajes.
* Matriz de **Hard Limits**, **Soft Limits** y **Deseos Clave**.
* Consejos de comunicación y negociación para compartir en pareja.
* **Exportación a PDF:** Generación de un informe descargable completo con tablas y conclusiones vía `html2pdf.js`.



---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica completa.
* **CSS3:** Variables CSS, Flexbox/Grid, animaciones y diseño *responsive*.
* **JavaScript (Vanilla ES6+):** Lógica del test, motor de ramificación, cálculo de puntajes y manipulación del DOM.
* **Librerías Externas (CDN):**
* [html2pdf.js](https://www.google.com/search?q=https://github.com/eKoopmans/html2pdf.js) — Para la exportación a PDF directamente desde el navegador.
* Google Fonts — Tipografías *Playfair Display* y *Montserrat*.



---

## 🚀 Instalación y Uso

No requiere backend ni servidores web complejos. Al ser un proyecto cliente (*client-side*), funciona directamente en cualquier navegador moderno.

1. **Clonar el repositorio:**
```bash
git clone https://github.com/tu-usuario/test-autoexploracion-bdsm.git

```


2. **Navegar a la carpeta del proyecto:**
```bash
cd test-autoexploracion-bdsm

```


3. **Ejecutar el test:**
Simplemente abre el archivo `index.html` en tu navegador predeterminado (fácilmente con doble clic o arrastrándolo a una ventana de Chrome, Firefox, Edge o Safari).

---

## 📂 Estructura del Proyecto

```text
├── index.html        # Aplicación completa (HTML, CSS y JS integrados)
└── README.md         # Documentación del proyecto

```

---

## 🔒 Privacidad & Seguridad

* **Sin almacenamiento de datos:** Toda la información procesada durante el test permanece exclusivamente en la memoria local del navegador del usuario.
* **Sin registros externos:** Ningún resultado o respuesta se envía a servidores externos ni bases de datos. Al cerrar la pestaña o descargar el PDF, la sesión se reinicia por completo.

---

## 🤝 Contribuciones

¡Las contribuciones para mejorar la redacción de preguntas, agregar nuevas categorías o refinar el diseño son bienvenidas!

1. Haz un **Fork** de este repositorio.
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcionalidad`).
3. Haz un **Commit** con tus cambios (`git commit -m 'Añade nueva funcionalidad'`).
4. Haz un **Push** a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un **Pull Request**.

---

## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente.
