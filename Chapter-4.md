# Capítulo IV: Product Design

## 4.1. Style Guidelines

En esta sección, el equipo sienta las bases para contar con un repositorio centralizado, unificado y organizado de uso común para todo el equipo, que incluye *assets*, tipografías, componentes UI, reglas de espaciado e iconografía, con el fin de mantener una presentación visual consistente, intuitiva y enfocada. Para **Nubi**, el sistema de diseño tomó como referencia directa el template de la comunidad de Figma *"Solus – Mental Health & Wellness Website Template"*: se extrajeron sus valores reales de color (verde-azulado oscuro, crema, melocotón y los tres acentos cálidos) y su tipografía de titulares, reemplazando la propuesta cromática desaturada de una versión anterior del sistema. El tono de comunicación de Nubi se define en cuatro dimensiones: **cercano** (más que formal), **sereno** (más que eufórico), **claro** (más que técnico) y **respetuoso** (más que irreverente), de modo que tanto el niño o adolescente neurodivergente como su cuidador perciban una marca cálida y confiable, sin caer en un tono infantil ni en una estética clínica y fría.

### 4.1.1. General Style Guidelines

En esta sección se explican las decisiones y referencias visuales sobre Branding, Typography, Colors y Spacing que sostienen la identidad de Nubi.

**Paleta de Colores**

- **Colores Primarios**

<table>
  <thead>
    <tr>
      <th><strong>Código HEX</strong></th>
      <th><strong>Color</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>#00373E</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#00373E;"></div></td>
      <td><strong>Deep Teal:</strong> verde-azulado muy oscuro que funciona como color principal de marca: tipografía de encabezados, navegación activa y botones de llamada a la acción (CTA), incluyendo el acceso directo al Modo SOS. Al ser un tono oscuro, admite texto blanco con contraste alto sin necesitar variantes adicionales.</td>
    </tr>
    <tr>
      <td><strong>#EFC01D</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#EFC01D;"></div></td>
      <td><strong>Golden Yellow:</strong> tono dorado cálido usado en acentos secundarios, badges de plan destacado e íconos de autorregulación y perfil, aportando energía sin competir con el Deep Teal.</td>
    </tr>
    <tr>
      <td><strong>#F7F6F4</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#F7F6F4;border:1px solid #E4E1DB;"></div></td>
      <td><strong>Cream:</strong> blanco cálido que actúa como lienzo base de toda la aplicación, reduciendo el deslumbramiento de un blanco puro y aportando una sensación acogedora y ordenada.</td>
    </tr>
    <tr>
      <td><strong>#F9E6D0</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#F9E6D0;border:1px solid #E4E1DB;"></div></td>
      <td><strong>Peach:</strong> melocotón suave de referencia para fondos de sección alternos (hero, tarjetas destacadas), disponible en la paleta para futuras variaciones del layout.</td>
    </tr>
  </tbody>
</table>

- **Colores Secundarios**

<table>
  <thead>
    <tr>
      <th><strong>Código HEX</strong></th>
      <th><strong>Color</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>#4CCBBB</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#4CCBBB;"></div></td>
      <td><strong>Mint Teal:</strong> tono fresco asociado a la Comunicación Asistida (CAA) y a los enlaces informativos. Transmite claridad y apertura al diálogo.</td>
    </tr>
    <tr>
      <td><strong>#F39CAC</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#F39CAC;"></div></td>
      <td><strong>Blossom Pink:</strong> acento afectivo reservado para la Red de Apoyo y Seguimiento: recomendaciones, notas del cuidador y mensajes de acompañamiento.</td>
    </tr>
    <tr>
      <td><strong>#E4E1DB</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#E4E1DB;"></div></td>
      <td><strong>Warm Grey:</strong> gris cálido destinado a bordes, divisores y tarjetas en reposo, estructurando la interfaz sin distraer al usuario.</td>
    </tr>
    <tr>
      <td><strong>#8A8A8A</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#8A8A8A;"></div></td>
      <td><strong>Taupe:</strong> gris medio usado en texto secundario, metadatos y marcas de tiempo del historial de episodios.</td>
    </tr>
    <tr>
      <td><strong>#E0605B</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#E0605B;"></div></td>
      <td><strong>Coral Red (Error / Alerta):</strong> color de alta intensidad reservado exclusivamente para mensajes de error, campos inválidos o situaciones que requieren atención inmediata durante una crisis.</td>
    </tr>
    <tr>
      <td><strong>#4FAE7B</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#4FAE7B;"></div></td>
      <td><strong>Leaf Green (Éxito):</strong> tono orgánico usado en confirmaciones de guardado, episodios cerrados correctamente y logros de autorregulación.</td>
    </tr>
    <tr>
      <td><strong>#EFC01D</strong></td>
      <td><div style="width:60px;height:40px;border-radius:6px;background:#EFC01D;"></div></td>
      <td><strong>Golden Yellow (Aviso):</strong> el mismo dorado de acento se reutiliza como color de aviso en recordatorios no urgentes, como perfiles incompletos o sugerencias pendientes de revisar.</td>
    </tr>
  </tbody>
</table>

Todas las combinaciones de texto sobre fondo respetan un contraste mínimo de 4.5:1 (Nivel AA de WCAG). Al ser Deep Teal un tono muy oscuro, admite texto blanco directamente en botones y bloques sólidos sin necesitar una variante adicional; en cambio, un texto blanco sobre Golden Yellow, Mint Teal o Blossom Pink no alcanza ese mínimo, por lo que los botones y etiquetas construidos sobre estos tres acentos usan texto en **Deep Teal** en lugar de blanco.

---

**Fonts**

Adoptamos la combinación tipográfica del template de referencia: **Bricolage Grotesque** para titulares e **Inter** para texto de cuerpo, equilibrando el carácter expresivo y contemporáneo de la marca con la legibilidad que necesitan niños, adolescentes neurodivergentes y sus cuidadores.

- **Bricolage Grotesque (Titulares):** tipografía grotesca de proporciones amplias y formas geométricas que se usa en encabezados (Display a H3), nombres de herramientas y botones de acción principal. Su carácter contemporáneo y seguro refuerza la identidad de marca heredada del template Solus, sin resultar infantil ni clínico.
- **Inter (Texto de cuerpo e interfaz):** familia Sans-Serif de alta legibilidad usada en párrafos, etiquetas de campos, mensajes del sistema y entradas de datos, garantizando lectura fluida incluso en momentos de sobreestimulación.
- **Escala tipográfica:** Display (42px), H1 (32px), H2 (24px), H3 (18px), Body Grande (16px), Body (14px) y Caption (12px), manteniendo una jerarquía ordenada entre mensajes de contención, títulos de módulo y metadatos.
- **Reglas de legibilidad:** interlineado mínimo de 1.4× en textos continuos, ancho de renglón máximo de 70 caracteres y prohibición de mayúsculas sostenidas en etiquetas. Ningún estado de la interfaz se comunica únicamente por color o tipografía.

---

**Espaciado y márgenes**

**Ritmo 8-pt recomendado:** el sistema completo se apoya en múltiplos de **8px** (con sub-múltiplos de 4px para ajustes micro), desde **4XS** (4px) hasta **4XL** (96px), manteniendo un orden matemático y predecible en todo el layout.

**Márgenes generales y contenedores:** las tarjetas mantienen un *padding* interno constante de **24px** en sus cuatro lados, clave para no saturar visualmente pantallas como el tablero CAA o el historial de episodios.

**Márgenes alrededor de elementos interactivos:** se mantiene un mínimo de **16px** entre botones, campos de formulario y tarjetas seleccionables adyacentes, para evitar pulsaciones accidentales durante un episodio de crisis.

**Interlineado en textos:** se aplica un valor de **1.4× a 1.5×** el tamaño de fuente para garantizar una lectura cómoda de las guías del Modo SOS y las recomendaciones del cuidador.

**Separación ícono–texto:** se define un espaciado fijo de **8px** entre el ícono y su etiqueta correspondiente en botones, pictogramas y ítems de menú.

---

**Branding y logo**

La identidad visual de **Nubi** se construyó para transmitir calma y acompañamiento cercano, evitando cualquier lectura clínica o corporativa fría:

- **Símbolo de acompañamiento (Isotipo):** una forma de gota/nube estilizada con un trazo curvo que sugiere una leve sonrisa, evocando **calma, contención y cercanía**. Su silueta redondeada, sin ángulos agudos, refuerza el mismo principio de suavidad aplicado en la iconografía y los botones *pill-shape*.
- **Identidad cromática:** la marca se apoya principalmente en **Deep Teal (#00373E)** y **Golden Yellow (#EFC01D)** sobre fondos en **Cream (#F7F6F4)**. Esta combinación, heredada del template Solus, busca transmitir calidez humana y serenidad, en contraste con la frialdad típica de una app clínica.
- **Naming y tipografía:** el nombre **"Nubi"** evoca la imagen de una nube pequeña y cercana, fácil de pronunciar y recordar tanto para el cuidador como para el niño o adolescente. Se presenta en Bricolage Grotesque para conservar el carácter contemporáneo de la marca en cualquier punto de contacto.

### 4.1.2. Web Style Guidelines

Esta sección explica e ilustra las decisiones sobre los estándares visuales y de interacción de Nubi para interfaces web responsivas (Landing Page y Web Application), partiendo del sistema de diseño definido en las General Style Guidelines.

**Estructura de la página**

La interfaz web de Nubi se organiza en tres zonas funcionales: un encabezado fijo (Header), un área de contenido central (Body) y un pie de página informativo (Footer), garantizando orientación permanente y coherencia entre el Landing Page y la Web Application.

<table>
  <thead>
    <tr>
      <th><strong>Ubicación</strong></th>
      <th><strong>Contenido</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Parte superior fija (sticky)</strong></td>
      <td>
        <strong>Logotipo Nubi:</strong> posicionado a la izquierda; enlace directo al inicio.<br>
        <strong>Navegación por anclas:</strong> enlaces a Perfil, Modo SOS, Autocuidado, Comunicación, Apoyo, Planes y FAQ.<br>
        <strong>Acciones de cuenta:</strong> botón de texto "Iniciar sesión" y botón primario "Comenzar gratis".
      </td>
    </tr>
    <tr>
      <td><strong>Zona central de contenido</strong></td>
      <td>
        <strong>Landing Page:</strong> Hero, resultados esperados, bloques de valor (LS-01 a LS-05), cómo funciona, beneficios, planes, FAQ y formulario de contacto.<br>
        <strong>Web Application:</strong> panel de inicio con estado del usuario, alertas, accesos directos y contenido propio de cada Bounded Context.<br>
        <strong>Espaciado entre bloques:</strong> separación de 32–64px entre secciones para evitar saturación visual.
      </td>
    </tr>
    <tr>
      <td><strong>Pie de página</strong></td>
      <td>
        <strong>Accesos de marca:</strong> logo, descripción breve y redes de contacto.<br>
        <strong>Enlaces agrupados:</strong> Producto, Compañía y Legal.<br>
        <strong>Cierre:</strong> año, titularidad y frase de marca.
      </td>
    </tr>
  </tbody>
</table>

---

**Tipografía**

En la interfaz web de escritorio, la jerarquía tipográfica de Nubi se aplica con valores responsivos mediante `clamp()`, manteniendo la legibilidad tanto en pantallas grandes como en resoluciones intermedias.

<table>
  <thead>
    <tr>
      <th><strong>Uso</strong></th>
      <th><strong>Fuente</strong></th>
      <th><strong>Tamaño / Peso</strong></th>
      <th><strong>Responsive (clamp)</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Display</strong></td>
      <td>Bricolage Grotesque</td>
      <td>42 px / Bold</td>
      <td>clamp(30px, 3vw + 14px, 42px)</td>
    </tr>
    <tr>
      <td><strong>Título H1</strong></td>
      <td>Bricolage Grotesque</td>
      <td>32 px / Bold</td>
      <td>clamp(24px, 2.2vw + 12px, 32px)</td>
    </tr>
    <tr>
      <td><strong>Título H2</strong></td>
      <td>Bricolage Grotesque</td>
      <td>24 px / SemiBold</td>
      <td>clamp(20px, 1.6vw + 10px, 24px)</td>
    </tr>
    <tr>
      <td><strong>Título H3 / Botón</strong></td>
      <td>Bricolage Grotesque</td>
      <td>18 px / SemiBold</td>
      <td>clamp(16px, 1vw + 9px, 18px)</td>
    </tr>
    <tr>
      <td><strong>Cuerpo de texto (Body Grande)</strong></td>
      <td>Inter</td>
      <td>16 px / Regular · lh 1.5</td>
      <td>clamp(15px, 0.5vw + 13px, 16px)</td>
    </tr>
    <tr>
      <td><strong>Texto de apoyo (Body)</strong></td>
      <td>Inter</td>
      <td>14 px / Regular · lh 1.5</td>
      <td>clamp(13px, 0.4vw + 12px, 14px)</td>
    </tr>
    <tr>
      <td><strong>Microcopy / Caption</strong></td>
      <td>Inter</td>
      <td>12 px / Medium · uppercase opcional</td>
      <td>Fijo — no escala</td>
    </tr>
  </tbody>
</table>

---

**Colores (paleta y contraste)**

La aplicación cromática en la interfaz web de Nubi sigue una distribución semántica estricta: **Deep Teal (#00373E)** concentra la energía de la acción y la tipografía principal, y **Cream (#F7F6F4)** actúa como lienzo base.

<table>
  <thead>
    <tr>
      <th><strong>Uso en interfaz web</strong></th>
      <th><strong>Color / HEX</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Botón CTA principal, acceso al Modo SOS, tipografía, navegación activa</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#00373E;margin-bottom:4px;"></div><code>#00373E</code></td>
      <td><strong>Deep Teal:</strong> concentra la llamada a la acción en botones "Comenzar gratis", "Crear cuenta y activarlo" y el acceso directo al Modo SOS, además de servir como color de texto principal. Al ser oscuro, admite texto blanco directo con contraste ≥ 4.5:1.</td>
    </tr>
    <tr>
      <td><strong>Fondo de tarjeta seleccionada, hover suave, chip activo</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#D9E4E3;margin-bottom:4px;border:1px solid #E4E1DB;"></div><code>#D9E4E3</code></td>
      <td><strong>Deep Teal 200:</strong> estado de selección activa en tarjetas de estímulo y pictogramas favoritos, sin la intensidad del color principal.</td>
    </tr>
    <tr>
      <td><strong>Acento secundario, badge de plan destacado</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#EFC01D;margin-bottom:4px;"></div><code>#EFC01D</code></td>
      <td><strong>Golden Yellow:</strong> resalta el plan "Más elegido" y acentúa íconos de Perfil y Autorregulación. Texto en Deep Teal para garantizar contraste ≥ 4.5:1.</td>
    </tr>
    <tr>
      <td><strong>Fondo general de la aplicación, superficies base</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#F7F6F4;margin-bottom:4px;border:1px solid #E4E1DB;"></div><code>#F7F6F4</code></td>
      <td><strong>Cream:</strong> lienzo principal de la interfaz. Evita el deslumbramiento de un blanco puro y aporta una sensación acogedora al Landing Page y la Web Application.</td>
    </tr>
    <tr>
      <td><strong>Comunicación CAA, enlaces informativos</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#4CCBBB;margin-bottom:4px;"></div><code>#4CCBBB</code></td>
      <td><strong>Mint Teal:</strong> tablero de pictogramas, enlaces y estados "Información". Aporta frescura sin competir con el Deep Teal principal.</td>
    </tr>
    <tr>
      <td><strong>Red de Apoyo, recomendaciones, mensajes afectivos</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#F39CAC;margin-bottom:4px;"></div><code>#F39CAC</code></td>
      <td><strong>Blossom Pink:</strong> acentos en el módulo de seguimiento y recomendaciones personalizadas para el cuidador.</td>
    </tr>
    <tr>
      <td><strong>Bordes, divisores, tarjetas en reposo</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#E4E1DB;margin-bottom:4px;"></div><code>#E4E1DB</code></td>
      <td><strong>Warm Grey:</strong> delimita tarjetas, campos de formulario y secciones sin introducir ruido visual.</td>
    </tr>
    <tr>
      <td><strong>Error, campos inválidos, Modo SOS en curso</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#E0605B;margin-bottom:4px;"></div><code>#E0605B</code></td>
      <td><strong>Coral Red:</strong> exclusivo para mensajes de error, validaciones fallidas y el estado "episodio en curso" del Modo SOS.</td>
    </tr>
    <tr>
      <td><strong>Éxito, episodio cerrado, mensaje enviado</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#4FAE7B;margin-bottom:4px;"></div><code>#4FAE7B</code></td>
      <td><strong>Leaf Green:</strong> confirmaciones de guardado, episodios finalizados y envío exitoso del formulario de contacto.</td>
    </tr>
    <tr>
      <td><strong>Aviso, recordatorio no urgente</strong></td>
      <td><div style="width:60px;height:36px;border-radius:6px;background:#EFC01D;margin-bottom:4px;"></div><code>#EFC01D</code></td>
      <td><strong>Golden Yellow:</strong> perfiles incompletos, sensibilidades no registradas o sugerencias pendientes de revisión.</td>
    </tr>
  </tbody>
</table>

---

**Iconografía**

La iconografía de Nubi mantiene un estilo lineal (*outline*) coherente con el carácter contemporáneo de Bricolage Grotesque, actuando como canal de comunicación alternativo para usuarios con dificultades en el procesamiento del lenguaje escrito.

<table>
  <thead>
    <tr>
      <th><strong>Aspecto</strong></th>
      <th><strong>Especificación</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Estilo</strong></td>
      <td>Trazo lineal (*outline*), extremos y esquinas redondeadas, grosor de trazo constante de 2px. Se evitan bordes afilados o ángulos agudos que transmitan tensión visual.</td>
    </tr>
    <tr>
      <td><strong>Tamaños</strong></td>
      <td>16px para íconos integrados en línea de texto (*inline*); 24px como estándar en botones y barras de herramientas; 32px en accesos de navegación principal y estados destacados.</td>
    </tr>
    <tr>
      <td><strong>Color según estado</strong></td>
      <td>#00373E en acciones primarias activas y navegación general; #8A8A8A en estados inactivos; #E0605B en alerta; #4FAE7B en confirmación; #EFC01D en aviso.</td>
    </tr>
    <tr>
      <td><strong>Catálogo principal</strong></td>
      <td>Inicio, Comunicación (tableros CAA), Autocuidado (autorregulación), Alerta / Crisis (Modo SOS), Ajustes, Perfil, Notificación y Nubi / Calma (símbolo identitario).</td>
    </tr>
    <tr>
      <td><strong>Accesibilidad</strong></td>
      <td>Todo ícono interactivo incluye `aria-label` descriptivo o texto visible acompañante. Ningún estado depende exclusivamente del ícono sin etiqueta.</td>
    </tr>
    <tr>
      <td><strong>Espaciado ícono–texto</strong></td>
      <td>Separación fija de 8px entre el ícono y su etiqueta, conforme al ritmo 8-pt del sistema general.</td>
    </tr>
  </tbody>
</table>

---

**Componentes clave (web)**

Los siguientes componentes conforman el vocabulario visual interactivo de la interfaz web de Nubi, usando **Deep Teal** y **Golden Yellow** como ejes cromáticos principales.

<table>
  <thead>
    <tr>
      <th><strong>Componente</strong></th>
      <th><strong>Estilo base</strong></th>
      <th><strong>Variantes / Estados</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="3" style="background-color:#00373E;color:#F7F6F4;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">BOTONES</td>
    </tr>
    <tr>
      <td><strong>Botón primario (CTA)</strong></td>
      <td>Fondo #00373E · texto #FFFFFF · Bricolage Grotesque 18px Bold · <em>pill-shape</em> (radio 100%) · padding 12px 24px.</td>
      <td><strong>Hover:</strong> fondo oscurecido a #002930. <strong>Focus:</strong> anillo 2.5px #4CCBBB. <strong>Disabled:</strong> fondo #E4E1DB · texto #8A8A8A.</td>
    </tr>
    <tr>
      <td><strong>Botón secundario</strong></td>
      <td>Borde 1.5px #00373E · fondo transparente · texto #00373E · Bricolage Grotesque 16px SemiBold · <em>pill-shape</em>.</td>
      <td><strong>Hover:</strong> fondo #EAF0EF. <strong>Focus:</strong> anillo 2.5px #4CCBBB. <strong>Disabled:</strong> borde y texto #E4E1DB.</td>
    </tr>
    <tr>
      <td><strong>Botón de texto / terciario</strong></td>
      <td>Sin fondo ni borde · texto #00373E · Inter 14px Medium.</td>
      <td><strong>Hover:</strong> subrayado. Reservado para acciones de bajo impacto ("Omitir", "Iniciar sesión").</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#00373E;color:#F7F6F4;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">FORMULARIOS E INPUTS</td>
    </tr>
    <tr>
      <td><strong>Campo de texto (Input)</strong></td>
      <td>Borde 1.5px #E4E1DB · fondo #F7F6F4 · Inter 16px Regular · radio 12px · padding 12px 16px.</td>
      <td><strong>Focus:</strong> borde #4CCBBB + anillo suave. <strong>Error:</strong> borde #E0605B + ícono y mensaje orientador. <strong>Completado:</strong> borde #4FAE7B.</td>
    </tr>
    <tr>
      <td><strong>Selector de Intensidad Emocional</strong></td>
      <td>Riel #D9E4E3 · relleno de progreso #4CCBBB · control circular blanco con borde #4CCBBB.</td>
      <td>Cuatro niveles: Calma, Inquieto, Alterado, Crisis. El nivel activo se refuerza con texto, nunca solo con color.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#00373E;color:#F7F6F4;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">TARJETAS</td>
    </tr>
    <tr>
      <td><strong>Tarjeta de estímulo / pictograma</strong></td>
      <td>Fondo #F7F6F4 · borde 1px #E4E1DB · radio 20px · padding 24px.</td>
      <td><strong>Hover / seleccionada:</strong> fondo #EAF0EF + borde #00373E. Badge de categoría en esquina superior (Mint Teal, Blossom Pink o Golden Yellow según el módulo).</td>
    </tr>
    <tr>
      <td><strong>Tarjeta de episodio (historial)</strong></td>
      <td>Fondo #F7F6F4 · fecha en Inter 12px #8A8A8A · estado en Bricolage Grotesque 14px Bold.</td>
      <td><strong>Finalizado:</strong> borde izquierdo #4FAE7B. <strong>Anticipado:</strong> borde izquierdo #EFC01D. <strong>En curso:</strong> borde izquierdo #E0605B.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#00373E;color:#F7F6F4;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">NAVEGACIÓN</td>
    </tr>
    <tr>
      <td><strong>Barra de navegación superior</strong></td>
      <td>Fondo #F7F6F4 (sticky) · ítems Inter 14px Medium #00373E · separación 24px entre ítems.</td>
      <td><strong>Activo:</strong> texto #00373E + subrayado. <strong>Hover:</strong> fondo #EAF0EF. <strong>Deshabilitado:</strong> opacidad 40%.</td>
    </tr>
    <tr>
      <td><strong>Migas de pan (Breadcrumbs)</strong></td>
      <td>Inter 14px Regular #8A8A8A · último ítem #00373E Bold.</td>
      <td>Máximo 4 niveles visibles. El nivel activo no es enlace. Separación 8px entre ítems.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#00373E;color:#F7F6F4;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">NOTIFICACIONES Y ALERTAS</td>
    </tr>
    <tr>
      <td><strong>Toast / confirmación</strong></td>
      <td>Fondo según estado: #4FAE7B (éxito), #E0605B (error), #EFC01D (aviso) · texto #00373E · radio 12px · padding 12px 20px.</td>
      <td><strong>Posición:</strong> esquina inferior. <strong>Duración:</strong> 3–5s con cierre manual. Ícono de 20px a la izquierda del texto.</td>
    </tr>
    <tr>
      <td><strong>Banner de alerta inline (Modo SOS)</strong></td>
      <td>Fondo #FBEAEA · borde izquierdo 4px #E0605B · texto Inter 14px #00373E · radio 8px · padding 12px 16px.</td>
      <td>Usado para episodios en curso o pasos obligatorios sin revisar. Ícono de alerta 20px #E0605B a la izquierda.</td>
    </tr>
  </tbody>
</table>

---

**Diseño responsivo**

Nubi adopta un enfoque de diseño responsivo que garantiza una experiencia óptima en escritorio, tableta y móvil, priorizando que toda funcionalidad disponible en escritorio sea igualmente accesible y operable en pantallas pequeñas durante un momento de crisis.

<table>
  <thead>
    <tr>
      <th><strong>Dispositivo</strong></th>
      <th><strong>Ancho</strong></th>
      <th><strong>Columnas</strong></th>
      <th><strong>Gutter</strong></th>
      <th><strong>Especificaciones</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Mobile</strong></td>
      <td>≤ 768 px</td>
      <td>4</td>
      <td>16 px</td>
      <td>Header compacto con menú hamburguesa. Bloques de valor en una sola columna. Acceso al Modo SOS siempre visible. Márgenes laterales de 20px.</td>
    </tr>
    <tr>
      <td><strong>Tablet</strong></td>
      <td>769–1024 px</td>
      <td>8</td>
      <td>20 px</td>
      <td>Navegación superior completa. Tarjetas de estímulo y pictogramas en 2 columnas. Secciones de valor en distribución apilada.</td>
    </tr>
    <tr>
      <td><strong>Desktop</strong></td>
      <td>≥ 1025 px</td>
      <td>12</td>
      <td>24 px</td>
      <td>Max-width de contenedor: 1200px, centrado. Bloques de valor en dos columnas (texto + visual). Planes y FAQ en formato de grilla.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th><strong>Requisito</strong></th>
      <th><strong>Valor recomendado / Especificación</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Objetivos táctiles mínimos</strong></td>
      <td>48 × 48 px en todos los breakpoints, para tolerar temblores o baja precisión motriz durante el estrés.</td>
    </tr>
    <tr>
      <td><strong>Separación entre controles</strong></td>
      <td>Mínimo 16px entre botones, campos y elementos interactivos adyacentes.</td>
    </tr>
    <tr>
      <td><strong>Indicador de foco visible</strong></td>
      <td>Anillo de 2.5px en #4CCBBB para todo elemento interactivo, nunca eliminado por estética.</td>
    </tr>
  </tbody>
</table>

Los estándares aquí establecidos constituyen la referencia normativa para la implementación del Landing Page y la Web Application de Nubi. Cualquier componente nuevo que se incorpore al sistema deberá respetar las especificaciones de color, tipografía, espaciado e interacción definidas en esta sección.

## 4.2. Information Architecture.

En esta sección el equipo plantea las decisiones y el sustento que dirigen la manera cómo se organiza el contenido en las experiencias del Landing Page y de la Web Application de Nubi. Estas decisiones buscan que los visitantes (cuidadores, educadores y terapeutas que aún no se han registrado) y los usuarios ya registrados (cuidadores y usuarios neurodivergentes) se adapten con facilidad a cada producto y encuentren lo que necesitan sin esfuerzo, incluso en momentos de estrés o sobrecarga sensorial. Las decisiones se estructuran alrededor de los 5 Bounded Contexts definidos en el Capítulo III (Perfil y Personalización, Gestión de Crisis / Modo SOS, Autorregulación, Comunicación Asistida CAA, y Red de Apoyo y Seguimiento).

### 4.2.1. Organization Systems.

Nubi combina distintos sistemas de organización visual según el objetivo de cada grupo de contenido, y distintos esquemas de categorización según la naturaleza de la información que agrupan.

**Sistemas de organización visual aplicados:**

* **Organización jerárquica (visual hierarchy):** se aplica en el Panel de inicio del cuidador (Home) y en el Perfil del usuario neurodivergente. El estado actual del usuario, las alertas y el acceso al Modo SOS reciben la mayor jerarquía visual (tamaño, contraste y posición superior), mientras que las recomendaciones y accesos secundarios se ubican en niveles de menor peso visual, siguiendo la escala tipográfica y cromática definida en la sección 4.1.
* **Organización secuencial (step-by-step to accomplish):** se aplica en la guía del Modo SOS y en el flujo de autorregulación con temporizador de calma, donde el contenido se presenta un paso a la vez para evitar la sobrecarga cognitiva durante una crisis, permitiendo solo avanzar o retroceder de forma lineal.
* **Organización matricial:** se aplica en el Tablero de Comunicación Aumentativa y Alternativa (CAA) y en la galería de estímulos de autorregulación, donde los pictogramas y estímulos se despliegan en una cuadrícula que combina dos dimensiones de clasificación (categoría y frecuencia de uso/favoritos), permitiendo el reconocimiento visual rápido por sobre la lectura secuencial.

**Esquemas de categorización de contenido aplicados:**

* **Por tópicos:** utilizado en el Tablero CAA (categorías como necesidades básicas, emociones, actividades) y en las recomendaciones personalizadas (agrupadas por tipo de situación: sensorial, comunicacional, conductual).
* **Cronológico:** utilizado en el Historial de episodios y en el historial de solicitudes de ayuda, donde los registros se listan del más reciente al más antiguo y pueden filtrarse por rango de fechas.
* **Según audiencia (grupos de usuarios):** utilizado tanto en el Landing Page como en la Web Application, diferenciando el contenido dirigido al cuidador (gestión de perfiles, historial, recomendaciones) del contenido dirigido al usuario neurodivergente (autorregulación, comunicación, solicitud de ayuda).
* **Alfabético:** utilizado de forma puntual en listados extensos que no cuentan con un criterio temporal o de frecuencia propio, como el listado de condiciones/diagnósticos disponibles al registrar el perfil del usuario.

### 4.2.2. Labeling Systems.

Las etiquetas de Nubi se definen priorizando la menor cantidad de palabras posible y un lenguaje claro y no técnico, de forma que cuidadores, educadores y usuarios neurodivergentes puedan anticipar qué encontrarán detrás de cada etiqueta sin ambigüedad. Cada etiqueta de navegación principal se asocia, en la mente del usuario, con un conjunto de contenido relacionado que no necesariamente está agrupado en un mismo lugar (por ejemplo, la etiqueta `Alerta / Crisis` asocia el acceso inmediato al Modo SOS sin necesidad de explicarlo cada vez).

| Etiqueta | Bounded Context asociado | Contenido que representa |
|---|---|---|
| `Inicio` | Red de Apoyo y Seguimiento | Panel general del cuidador: estado del usuario, alertas y accesos directos. |
| `Perfil` | Perfil y Personalización | Datos del usuario neurodivergente, sensibilidades, diagnóstico y cuidadores asociados. |
| `Modo SOS` / `Alerta` | Gestión de Crisis (Modo SOS) | Activación de la guía de actuación paso a paso durante una crisis. |
| `Autocuidado` | Autorregulación | Estímulos visuales/auditivos, temporizador de calma y modo de baja estimulación. |
| `Comunicación` | Comunicación Asistida (CAA) | Tablero de pictogramas para expresar necesidades. |
| `Ayuda` | Red de Apoyo y Seguimiento | Solicitud de ayuda al cuidador y su seguimiento. |
| `Historial` | Red de Apoyo y Seguimiento | Episodios registrados y notas asociadas. |
| `Recomendaciones` | Red de Apoyo y Seguimiento | Guías de actuación sugeridas según el perfil del usuario. |
| `Notificación` | Red de Apoyo y Seguimiento | Avisos push de alertas, solicitudes de ayuda y recordatorios. |
| `Ajustes` | Perfil y Personalización | Preferencias de cuenta, idioma, tema y notificaciones. |

Se evita el uso de sinónimos distintos para un mismo concepto entre el Landing Page y la Web Application (por ejemplo, siempre `Modo SOS`, nunca alternado con `Emergencia` o `Auxilio`), de forma que la etiqueta aprendida durante la exploración del sitio estático se mantenga vigente al ingresar a la aplicación.

### 4.2.3. SEO Tags and Meta Tags

Se definen los SEO Tags y Meta Tags mínimos (Title, Description, Keywords y Author) para las páginas principales del Landing Page y de la Web Application, alineados a las 5 secciones definidas como Landing Page Stories en el Capítulo III (LS-01 a LS-05).

**Landing Page:**

| Página / Sección | Title | Meta Description | Keywords | Author |
|---|---|---|---|---|
| Inicio (Hero) | Nubi \| Acompañamiento para niños y adolescentes neurodivergentes | Nubi ayuda a cuidadores y familias a acompañar a niños y adolescentes con TEA, TDAH o TOC durante crisis sensoriales, con guías paso a paso y herramientas de autorregulación. | nubi, neurodivergencia, TEA, TDAH, cuidadores, modo SOS | Equipo Nubi |
| Perfil y Personalización (LS-01) | Nubi \| Perfiles personalizados para cada usuario | Descubre cómo Nubi personaliza sensibilidades, diagnóstico y estímulos según el perfil de cada niño o adolescente neurodivergente. | perfil neurodivergente, personalización, sensibilidades sensoriales | Equipo Nubi |
| Modo SOS (LS-02) | Nubi \| Modo SOS: guías paso a paso ante una crisis | Conoce cómo el Modo SOS de Nubi guía al cuidador con pasos claros durante un episodio de desregulación. | modo SOS, crisis, guía paso a paso, desregulación emocional | Equipo Nubi |
| Autorregulación (LS-03) | Nubi \| Herramientas de autorregulación sensorial | Estímulos visuales, auditivos y temporizador de calma para ayudar a recuperar la calma tras una sobrecarga sensorial. | autorregulación, sobrecarga sensorial, estímulos, calma | Equipo Nubi |
| Comunicación CAA (LS-04) | Nubi \| Tablero de Comunicación Aumentativa y Alternativa | Un tablero de pictogramas que permite comunicar necesidades básicas sin depender del habla. | CAA, pictogramas, comunicación aumentativa, comunicación alternativa | Equipo Nubi |
| Red de Apoyo (LS-05) | Nubi \| Seguimiento y recomendaciones para cuidadores | Historial de episodios y recomendaciones personalizadas para acompañar de forma más efectiva. | seguimiento, recomendaciones, historial de episodios, cuidadores | Equipo Nubi |

**Web Application:**

| Vista | Title | Meta Description | Keywords | Author |
|---|---|---|---|---|
| Inicio de sesión | Iniciar sesión \| Nubi | Accede a tu cuenta de Nubi para gestionar el perfil y el acompañamiento del usuario a tu cargo. | iniciar sesión, nubi, acceso cuidadores | Equipo Nubi |
| Panel de inicio (Home) | Panel de inicio \| Nubi | Consulta el estado actual, alertas recientes y accesos directos a las herramientas de Nubi. | panel de inicio, estado del usuario, alertas | Equipo Nubi |
| Modo SOS | Modo SOS \| Nubi | Guía paso a paso para actuar con seguridad durante un episodio de desregulación. | modo sos, guía de crisis, pasos de actuación | Equipo Nubi |
| Autorregulación | Autorregulación \| Nubi | Selecciona estímulos visuales o auditivos y usa el temporizador de calma. | autorregulación, estímulos, temporizador de calma | Equipo Nubi |
| Tablero CAA | Comunicación \| Nubi | Selecciona pictogramas para comunicar una necesidad. | tablero caa, pictogramas, comunicación | Equipo Nubi |

Nota: al tratarse de una Web Application que requiere autenticación para acceder a la mayoría de sus vistas, las páginas internas priorizan Meta Tags orientados a accesibilidad y consistencia de marca antes que a posicionamiento orgánico (SEO), mientras que el Landing Page concentra el esfuerzo de SEO al ser la puerta de entrada pública e indexable del producto.

### 4.2.4. Searching Systems.

Nubi ofrece mecanismos de búsqueda acotados y simples, priorizando filtros predefinidos sobre la búsqueda libre por texto, con el fin de reducir la carga cognitiva del usuario y evitar que se sienta perdido entre el volumen de información:

* **Historial de episodios:** el cuidador cuenta con un filtro por rango de fechas (US-38) que reduce el listado cronológico a un periodo específico. Los resultados se presentan como una lista de tarjetas ordenadas de la más reciente a la más antigua, cada una con fecha, duración y estado del episodio.
* **Tablero CAA:** el usuario y el cuidador cuentan con un filtro por categoría de pictogramas (necesidades básicas, emociones, actividades) y con una sección de favoritos que actúa como acceso directo a los pictogramas más utilizados. Los resultados se presentan como una cuadrícula de íconos con su etiqueta.
* **Galería de estímulos de autorregulación:** cuenta con un filtro por tipo de estímulo (visual/auditivo) y con una sección de favoritos. Los resultados se presentan como una cuadrícula de tarjetas con vista previa del estímulo.
* **Recomendaciones:** cuentan con un filtro por tópico (sensorial, comunicacional, conductual) y con una sección de recomendaciones favoritas. Los resultados se presentan como una lista ordenada por relevancia, mostrando primero las recomendaciones generadas más recientemente.

Dado el alcance definido para los 5 Bounded Contexts, Nubi no incorpora un buscador de texto libre global: al tratarse de un volumen de contenido acotado y ya categorizado (perfiles, pictogramas, estímulos, episodios y recomendaciones asociados a un número reducido de usuarios por cuenta), los filtros predefinidos son suficientes para que el cuidador o el usuario neurodivergente encuentren lo que buscan sin la carga adicional de formular una consulta de texto.

### 4.2.5. Navigation Systems.

La navegación de Nubi combina accesos globales persistentes con recorridos guiados y lineales, priorizando siempre que el usuario neurodivergente o el cuidador puedan llegar a la ayuda inmediata en el menor número de pasos posible:

* **Navegación global (Web Application):** una barra de navegación superior (ver sección 4.1.2, Componentes clave — Navegación) mantiene visibles en todo momento los módulos principales (`Inicio`, `Perfil`, `Autocuidado`, `Comunicación`, `Ajustes`), permitiendo saltar entre Bounded Contexts sin perder el contexto de la sesión activa.
* **Acceso directo persistente al Modo SOS:** el acceso a la guía de crisis (US-12) se mantiene visible desde cualquier pantalla de la aplicación mediante un elemento de navegación de alta prioridad visual, de forma que el cuidador nunca necesite más de una acción para llegar a él, incluso si se desactivó el acceso directo (en cuyo caso queda disponible desde el menú principal).

Adicionalmente, cada Bounded Context aplica una técnica de navegación distinta según el tipo de tarea que soporta:

| Contexto | Técnica de navegación |
|---|---|
| Modo SOS | Navegación lineal guiada (Siguiente / Atrás) entre los pasos de la guía, sin acceso a otras secciones hasta finalizar o cerrar el episodio. |
| Autorregulación | Navegación por selección directa dentro de una cuadrícula (sin jerarquía de pasos), regresando siempre a la galería principal. |
| Tablero CAA | Navegación por categorías con cambio de contexto inmediato al seleccionar un pictograma (reproducción de audio y notificación), sin salir del tablero. |
| Red de Apoyo y Seguimiento | Navegación jerárquica desde el panel de inicio hacia el detalle (episodio, solicitud o recomendación específica), con retorno directo al nivel anterior. |
| Perfil y Personalización | Navegación por pestañas o secciones dentro de un mismo perfil (datos generales, sensibilidades, diagnóstico, cuidadores asociados). |

* **Cambio entre perfiles a cargo:** el cuidador con más de un perfil asociado navega entre ellos mediante un selector persistente (US-35), sin necesidad de cerrar sesión, evitando que la navegación entre usuarios interrumpa el flujo de la aplicación.
* **Navegación en el Landing Page:** se guía al visitante mediante desplazamiento por anclas (*anchor scroll*) entre las 5 secciones de valor (LS-01 a LS-05) accesibles desde la barra de navegación superior, y mediante llamados a la acción (*call-to-action*) al cierre de cada sección que redirigen al registro o inicio de sesión en la Web Application.
* **Migas de pan (Web):** como se describe en la sección 4.1.2 (Componentes clave — Navegación), se utilizan en las vistas de mayor profundidad (por ejemplo, dentro del Historial de episodios) para que el cuidador comprenda su ubicación exacta y pueda regresar a niveles anteriores sin depender del botón "Atrás" del navegador.

## 4.3 Landing Page UI Design

El Landing Page de Nubi traduce las decisiones de arquitectura de información de la sección 4.2 en una experiencia de una sola página, pensada para que un visitante (cuidador, educador o terapeuta que aún no se ha registrado) entienda en segundos qué resuelve Nubi y pueda avanzar hacia el registro sin fricción. La estructura respeta el esquema de categorización "según audiencia" y la organización jerárquica definidos en la sección 4.2.1: primero se comunica la propuesta de valor (Hero), el problema (Problema) y el proceso de adopción (Cómo funciona); luego se desarrolla cada una de las 5 Landing Page Stories del Capítulo III (LS-01 a LS-05: Perfil y Personalización, Modo SOS, Autorregulación, Comunicación CAA y Red de Apoyo) en el mismo orden en que fueron priorizadas en el Product Backlog; y finalmente se ubican los bloques de conversión y confianza (Planes, Testimonios, FAQ, Beneficios por rol, la sección "Conoce al equipo", el llamado a la acción final y un formulario de contacto para familias e instituciones), cerrando con el footer. La navegación superior utiliza el sistema de anclas (*anchor scroll*) descrito en la sección 4.2.5, reutilizando exactamente las mismas etiquetas definidas en el Labeling System (4.2.2) para que el visitante reconozca los mismos nombres al ingresar luego a la Web Application.

El wireframe y el mock-up se construyeron directamente en HTML/CSS, tomando como referencia directa el template de la comunidad de Figma *"Solus – Mental Health & Wellness Website Template"*: se extrajeron sus valores reales de color y tipografía a partir del código exportado en modo Dev de Figma, y se aplicaron al Design System de la sección 4.1 (tipografía Bricolage Grotesque/Inter, paleta Deep Teal/Golden Yellow/Cream con sus acentos secundarios, sistema de espaciado de 8pt, botones *pill-shape* y set de iconografía de 24px). El resultado se importó a Figma mediante un plugin de conversión HTML→Figma para su documentación y edición visual. El código fuente se encuentra en [`landing-page/`](../landing-page/index.html) del repositorio.

### 4.3.1 Landing Page Wireframe

Los wireframes representan la distribución base de cada sección antes de aplicar el acabado visual final. Permiten validar la jerarquía de información, el orden de lectura y la ubicación de los llamados a la acción definidos en la Arquitectura de Información (sección 4.2): jerarquía visual en el Hero y en la franja de resultados esperados, organización secuencial (*step-by-step*) en el bloque del Modo SOS, y organización matricial en la cuadrícula de pictogramas del bloque de Comunicación CAA. Se presenta la versión para Desktop Web Browser y Mobile Web Browser de cada sección.

- **Header (Navbar)**

  <p align="center">
    <img src="images/Chapter-IV/navbarWireframe.png" alt="Wireframe Header Navbar" width="800">
  </p>

- **Hero section**

  <p align="center">
    <img src="images/Chapter-IV/HeroSectionWireframe.png" alt="Wireframe Hero Section" width="800">
  </p>

- **Problema section**

  <p align="center">
    <img src="images/Chapter-IV/problemaWireframe.png" alt="Wireframe Problema Section" width="800">
  </p>

- **Cómo funciona section**

  <p align="center">
    <img src="images/Chapter-IV/FuncionalidadWireframe.png" alt="Wireframe Cómo Funciona Section" width="800">
  </p>

- **Perfil y Personalización section**

  <p align="center">
    <img src="images/Chapter-IV/PerfilyPersonalizacionWireframe.png" alt="Wireframe Perfil y Personalización Section" width="800">
  </p>

- **Modo SOS section**

  <p align="center">
    <img src="images/Chapter-IV/ModoSosWireframe.png" alt="Wireframe Modo SOS Section" width="800">
  </p>

- **Autorregulación section**

  <p align="center">
    <img src="images/Chapter-IV/AutorregulaciónWireframe.png" alt="Wireframe Autorregulación Section" width="800">
  </p>

- **Comunicación CAA section**

  <p align="center">
    <img src="images/Chapter-IV/ComunicacionCAAWireframe.png" alt="Wireframe Comunicación CAA Section" width="800">
  </p>

- **Red de Apoyo section**

  <p align="center">
    <img src="images/Chapter-IV/RedDeApoyoWireframe.png" alt="Wireframe Red de Apoyo Section" width="800">
  </p>

- **Planes section**

  <p align="center">
    <img src="images/Chapter-IV/PlanesWireframe.png" alt="Wireframe Planes Section" width="800">
  </p>

- **Testimonios section**

  <p align="center">
    <img src="images/Chapter-IV/TestimoniosWireframe.png" alt="Wireframe Testimonios Section" width="800">
  </p>

- **FAQ section**

  <p align="center">
    <img src="images/Chapter-IV/FAQWireframe.png" alt="Wireframe FAQ Section" width="800">
  </p>

- **Beneficios section**

  <p align="center">
    <img src="images/Chapter-IV/BeneficiosWireframe.png" alt="Wireframe Beneficios Section" width="800">
  </p>

- **Conoce al equipo section**

  <p align="center">
    <img src="images/Chapter-IV/ConoceAlEquipoWireframe.png" alt="Wireframe Conoce al Equipo Section" width="800">
  </p>

- **CTA final section**

  <p align="center">
    <img src="images/Chapter-IV/CTAWireframe.png" alt="Wireframe CTA Final Section" width="800">
  </p>

- **Formulario de Contacto section**

  <p align="center">
    <img src="images/Chapter-IV/FormularioWireframe.png" alt="Wireframe Formulario de Contacto Section" width="800">
  </p>

- **Footer section**

  <p align="center">
    <img src="images/Chapter-IV/FooterWireframe.png" alt="Wireframe Footer Section" width="800">
  </p>

### 4.3.2 Landing Page Mock-up

Los mock-ups incorporan el Design System de la sección 4.1 sobre la estructura ya validada en los wireframes: tipografía Bricolage Grotesque para titulares e Inter para texto de cuerpo, la paleta cromática (Deep Teal, Golden Yellow, Mint Teal, Blossom Pink y Cream como fondo base), botones con esquinas 100% redondeadas respetando un único botón primario por pantalla, y el grid de espaciado de 8pt tanto en el padding de las tarjetas como en la separación entre secciones. Sobre esta base se aplican además los criterios de diseño inclusivo definidos para Nubi: contraste mínimo AA (4.5:1) entre texto y fondo —el color principal Deep Teal es lo bastante oscuro para admitir texto blanco directo, mientras que el texto sobre Golden Yellow, Mint Teal o Blossom Pink usa Deep Teal en lugar de blanco— y estados de error o alerta comunicados siempre con ícono y texto, nunca solo con color. Cada bloque de valor (LS-01 a LS-05) reutiliza el mismo componente de tarjeta e iconografía de 24px definidos en la sección 4.1.2 (Iconografía), de modo que el visitante reconozca visualmente el mismo lenguaje al pasar de una sección a otra. El formulario de contacto, ubicado antes del footer, reutiliza el componente de Inputs definido en 4.1.2 (Componentes clave — Formularios e Inputs): campos con estado *Focus* (borde Mint Teal) y estado *Error* que combina borde en Coral Red con un ícono y un mensaje orientador (nunca solo color), además de un estado de confirmación tras el envío que refuerza el patrón de retroalimentación empática del sistema.

- **Header (Navbar)**

  <p align="center">
    <img src="images/Chapter-IV/navbarMockup.png" alt="Mockup Header Navbar" width="800">
  </p>

- **Hero section**

  <p align="center">
    <img src="images/Chapter-IV/HeroSectionMockup.png" alt="Mockup Hero Section" width="800">
  </p>

- **Problema section**

  <p align="center">
    <img src="images/Chapter-IV/problemaMockup.png" alt="Mockup Problema Section" width="800">
  </p>

- **Cómo funciona section**

  <p align="center">
    <img src="images/Chapter-IV/FuncionalidadMockup.png" alt="Mockup Cómo Funciona Section" width="800">
  </p>

- **Perfil y Personalización section**

  <p align="center">
    <img src="images/Chapter-IV/PerfilyPersonalizacionMockup.png" alt="Mockup Perfil y Personalización Section" width="800">
  </p>

- **Modo SOS section**

  <p align="center">
    <img src="images/Chapter-IV/ModoSosMockup.png" alt="Mockup Modo SOS Section" width="800">
  </p>

- **Autorregulación section**

  <p align="center">
    <img src="images/Chapter-IV/AutorregulaciónMockup.png" alt="Mockup Autorregulación Section" width="800">
  </p>

- **Comunicación CAA section**

  <p align="center">
    <img src="images/Chapter-IV/ComunicacionCAAMockup.png" alt="Mockup Comunicación CAA Section" width="800">
  </p>

- **Red de Apoyo section**

  <p align="center">
    <img src="images/Chapter-IV/RedDeApoyoMockup.png" alt="Mockup Red de Apoyo Section" width="800">
  </p>

- **Planes section**

  <p align="center">
    <img src="images/Chapter-IV/PlanesMockup.png" alt="Mockup Planes Section" width="800">
  </p>

- **Testimonios section**

  <p align="center">
    <img src="images/Chapter-IV/TestimoniosMockup.png" alt="Mockup Testimonios Section" width="800">
  </p>

- **FAQ section**

  <p align="center">
    <img src="images/Chapter-IV/FAQMockup.png" alt="Mockup FAQ Section" width="800">
  </p>

- **Beneficios section**

  <p align="center">
    <img src="images/Chapter-IV/BeneficiosMockup.png" alt="Mockup Beneficios Section" width="800">
  </p>

- **Conoce al equipo section**

  <p align="center">
    <img src="images/Chapter-IV/ConoceAlEquipoMockup.png" alt="Mockup Conoce al Equipo Section" width="800">
  </p>

- **CTA final section**

  <p align="center">
    <img src="images/Chapter-IV/CTAMockup.png" alt="Mockup CTA Final Section" width="800">
  </p>

- **Formulario de Contacto section**

  <p align="center">
    <img src="images/Chapter-IV/FormularioMockup.png" alt="Mockup Formulario de Contacto Section" width="800">
  </p>

- **Footer section**

  <p align="center">
    <img src="images/Chapter-IV/FooterMockup.png" alt="Mockup Footer Section" width="800">
  </p>

## 4.4 Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes

### 4.4.2 Web Applications Wireflow Diagrams

#### 4.4.2. Web Applications Wireflow Diagrams

**Segmento 1: Residentes en zonas de riesgo medio-alto**

**Segmento 2: Comerciantes en zonas de riesgo medio-alto**