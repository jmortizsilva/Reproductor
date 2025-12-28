# Reproductor de Vídeo Accesible

Reproductor de vídeo accesible implementado con Able Player, incluyendo subtítulos y audiodescripción.

## Características

- ✅ Totalmente accesible (WCAG 2.1)
- ✅ Subtítulos en español
- ✅ Audiodescripción mediante text-to-speech
- ✅ Controles de teclado personalizables
- ✅ Compatible con lectores de pantalla
- ✅ Transcripción interactiva automática
- ✅ Diseño responsive
- ✅ Personalización de preferencias de usuario

## Tecnologías

- [Able Player](https://ableplayer.github.io/ableplayer/) - Reproductor HTML5 accesible
- Personalizaciones de [tothomweb](https://tothomweb.com)
- jQuery 3.2.1
- js-cookie 3.0.1

## Estructura del Proyecto

```
/
├── index.html                      # Página principal
├── video_jose.mp4                  # Archivo de vídeo
├── video_jose_subtitulos.vtt       # Subtítulos en español
├── video_jose_audiodescripcion.vtt # Audiodescripción
├── custom-player.css               # Estilos personalizados
├── custom-player.js                # Scripts personalizados
├── ca.js, es.js, oc-aranes.js     # Traducciones personalizadas
├── build/                          # Archivos minificados de Able Player
├── button-icons/                   # Iconos del reproductor
└── translations/                   # Traducciones estándar
```

## Atajos de Teclado

Por defecto con **Alt + Control**:

- **P** o **Espacio**: Reproducir/Pausar
- **S**: Detener
- **R**: Reiniciar
- **C**: Activar/Desactivar subtítulos
- **D**: Activar/Desactivar descripciones
- **F**: Pantalla completa
- **M**: Silenciar/Activar sonido
- **Flechas**: Avanzar/Retroceder

## Documentación

- [Able Player - Documentación oficial](https://ableplayer.github.io/ableplayer/)
- [Implementación Standalone - tothomweb](https://ableplayer.tothomweb.dev/pages/implementacio-hc.html)

## Licencia

Este proyecto utiliza Able Player, licenciado bajo MIT License.
