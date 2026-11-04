# El Planeta de los Zafios II · Misión Amiguetes on Paradise

El videojuego de la segunda parte del libro de humor de Marco Antonio Saborido Domínguez. Calificación +18.

Ocho mundos con diez fases y un monstruo cada uno, fases de lucha uno contra uno, vuelos en el Falcon X, huidas, un partido de fútbol contra el Clan del Pelusa y, al final, la gran tangana del siglo. Tiene intro con los más de cien personajes del libro, narrador por voz y Zafiopedia.

## Jugar

- **Por WhatsApp:** `El_Planeta_de_los_Zafios_II.html` es el juego entero en un solo archivo. Se abre con Chrome.
- **Como app de Android:** pestaña **Releases** de este repositorio, archivo `Zafios-II.apk`.
- **En la web:** si activas GitHub Pages (carpeta `docs/`), desde Chrome en el móvil se puede instalar con menú ⋮ y «Instalar app».

## Sacar el APK

1. Pestaña **Actions**, flujo **Compilar APK**, botón **Run workflow**.
2. A los 10 minutos más o menos aparece en **Releases** como `Zafios-II.apk`.

Cada vez que se sube un `El_Planeta_de_los_Zafios_II.html` nuevo, el APK se vuelve a compilar solo.

## Carpetas

| Carpeta | Contenido |
|---|---|
| `El_Planeta_de_los_Zafios_II.html` | El juego |
| `app/` | Proyecto de la app de Android (Capacitor), iconos y pantalla de carga |
| `docs/` | Versión web instalable para GitHub Pages |
| `.github/workflows/compilar-apk.yml` | Compila el APK en GitHub |

Al actualizar el juego, copia también el HTML a `docs/index.html` para que la web quede igual.

Personajes en su mayoría ficticios: cualquier parecido con la realidad será responsabilidad suya.
