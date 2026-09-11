# Tzapopan

Cuatro páginas HTML autocontenidas de **Martín Maldonado**, elaboradas para la
Práctica Clínica Supervisada.

| Página | Contenido |
|---|---|
| [`index.html`](index.html) | **Índice.** Punto de entrada: enlaza las dos páginas con su descripción. |
| [`quien-soy.html`](quien-soy.html) | Recorrido biográfico por nueve ciudades, línea de tiempo con filtros y genograma familiar. |
| [`estilo-terapeutico.html`](estilo-terapeutico.html) | Diez apartados sobre la construcción del estilo terapéutico propio. |
| [`experiencia-matrix.html`](experiencia-matrix.html) | La experiencia matrix: once años institucionalizado, la salida a los veintitrés y lo que se hace con eso. |
| [`caso-karla.html`](caso-karla.html) | Presentación del caso clínico, anonimizada. |

## Uso

Cada archivo es una presentación tipo diapositivas que abre directamente en el
navegador. No requiere servidor ni instalación:

```bash
start index.html              # Windows
```

Desde el índice se llega a las dos páginas. La preferencia de tema
(claro / oscuro) se comparte entre las tres.

Navegación con `←` / `→`, `Space` y `Home` / `End`.

## Estructura

```
index.html            índice de entrada
quien-soy.html
estilo-terapeutico.html
experiencia-matrix.html
caso-karla.html
assets/
  Fotos/      imágenes personales (optimizadas: máx. 1920px, JPG q82)
  Lugares/    fotografías de ciudades para la galería
```

## Notas

- Las imágenes del repo están optimizadas para web (39 MB → 11 MB, −71 %).
  Los originales sin comprimir se conservan fuera del repositorio.
- El repositorio es **privado**: contiene material personal y familiar.
