# # Simulacro de Phishing - Página de Concienciación

## Descripción

Esta página HTML muestra un aviso informativo al usuario después de haber participado en un simulacro de phishing. Su objetivo es reforzar la formación en ciberseguridad mediante una explicación clara de lo ocurrido y la presentación de buenas prácticas para detectar futuros intentos de fraude.

La página está diseñada para mostrarse inmediatamente después de que el usuario introduzca sus credenciales en una página de prueba durante una campaña de concienciación.

## Características

- Diseño visual inspirado en alertas corporativas de seguridad.
- Mensaje educativo y no punitivo.
- Recomendaciones prácticas para identificar intentos de phishing.
- Panel de advertencia destacado sobre el riesgo real de este tipo de ataques.
- Totalmente responsive.
- Sin dependencias externas.
- Incluye una alerta sonora intermitente durante 5 segundos utilizando la Web Audio API.

## Estructura

### Banner de alerta

Contiene:

- Icono de advertencia.
- Título principal:
  
  > Has caído en un simulacro de phishing

### Mensaje principal

Informa al usuario de que:

- Ha introducido credenciales en una página no legítima.
- Se trata de un ejercicio controlado.
- No existe riesgo para su cuenta o datos.

### Advertencia destacada

Resalta las posibles consecuencias de un ataque real:

- Robo de credenciales.
- Acceso no autorizado al correo electrónico.
- Compromiso de documentos corporativos.
- Acceso a sistemas internos.

### Consejos de seguridad

Incluye recomendaciones como:

- Verificar siempre la URL.
- Desconfiar de mensajes con urgencia o amenazas.
- Revisar el destino real de los enlaces.
- Contactar con IT utilizando canales oficiales.

### Nota final

Invita al usuario a contactar con el equipo de Seguridad de la Información en caso de duda.

## Funcionalidad de audio

La página incorpora una señal sonora de advertencia:

- Duración aproximada: 5 segundos.
- Frecuencia: 880 Hz.
- Patrón: 200 ms de sonido y 300 ms de silencio.
- Volumen moderado.
- Compatible con las restricciones modernas de reproducción automática mediante interacción del usuario.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript Vanilla
- Web Audio API

## Casos de uso

Este recurso está pensado para:

- Campañas internas de phishing simulado.
- Programas de formación en ciberseguridad.
- Ejercicios de concienciación corporativa.
- Evaluación del nivel de madurez en seguridad de los empleados.

## Personalización

Se puede adaptar fácilmente:

- Colores corporativos.
- Logotipo de la organización.
- Mensajes informativos.
- Contacto del departamento de IT o Seguridad.
- Duración y características del aviso sonoro.

## Seguridad y privacidad

- No almacena información.
- No transmite datos a servicios externos.
- No utiliza cookies.
- Funciona completamente en el navegador del usuario.

## Instalación

1. Guardar el código como `index.html`.
2. Abrir el archivo en cualquier navegador moderno.

O bien:

```bash
python -m http.server 8080