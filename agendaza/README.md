# Agendaza · Visual Workspace

Espacio de trabajo para armar, probar y versionar las imágenes de publicación de **Agendaza** en App Store (iOS) y Play Store (Android).

---

## Estructura de carpetas

```
/
├── assets/          Logos usados en las imágenes
├── screenshots/     Capturas de pantalla de la app
│   └──0.1.0
├── mockups/         Mockups de Stores para probar cómo quedan
│   ├── playstore/   ...
│   └── applestore/  ...
│   └── banner/  ...
├── 0.1.0/           Imágenes generadas para cada version
├── 0.1.1/           ...
├── 0.1.2/           ...
└── README.md
```

> Ajustá los nombres de las carpetas si en tu workspace se llaman distinto.

### Qué va en cada carpeta

| Carpeta | Contenido |
|---|---|
| `assets/` | Logo de Agendaza (la "A", `adaptive-icon.png`) y logo de estonianport (`logo.png`). |
| `screenshots/` | Capturas reales de la app (Agenda, Reservar, Finanzas).|
| `mockups/` | Un mockup de Play Store y otro de App Store donde se van intercambiando las imágenes para ver cómo se ven en la ficha. |
| `0.x.x/` | Una carpeta por versión de la app, con las imágenes finales y de prueba que se generan para esa versión. |

---

## Flujo de trabajo

1. Sacar o actualizar las capturas en `screenshots/`.
2. Generar las 3 imágenes de publicación usando los logos de `assets/`.
3. Guardarlas en la carpeta de la versión (`0.1.x/`).
4. Probarlas en los mockups de `mockups/` y ajustar lo que haga falta.
5. Subir a las stores las imágenes de la versión correspondiente.

---

## Imágenes de publicación

### iOS
* **Capturas verticales:** 3 imágenes por versión
  * **Tamaño:** 1179 × 2556 px
  * **Nombre de archivo:** `iphone_N_1179x2556.png` *(N = 1, 2, 3)*
* **Banner:** 1 imagen por versión
  * **Tamaño:** 1920 × 1080 px
  * **Nombre de archivo:** `iphone_banner_1920x1080.png`

##

### Android
* **Capturas verticales:** 3 imágenes por versión
  * **Tamaño:** 720 × 1280 px
  * **Nombre de archivo:** `android_N_720x1280.png` *(N = 1, 2, 3)*
* **Banner:** 1 imagen por versión
  * **Tamaño:** 1024 × 500 px
  * **Nombre de archivo:** `android_banner_1024x500.png`
  
### Contenido de cada imagen

| # | Título | Subtítulo | Captura |
|---|---|---|---|
| 1 | CALENDARIO CON EVENTOS | Mantené el control de tus fechas y eventos registrados de forma simple | Agenda |
| 2 | GESTIONÁ TUS RESERVAS | Generá y administrá reservas completas paso a paso | Nueva reserva |
| 3 | SEGUIMIENTO DE PAGOS | Controlá tus ingresos, egresos y el balance de tu negocio | Finanzas |

### Estilo

#### v0.1.2
- Fondo blanco, sobrio y simple.
- Recuadro gris (`#F1F5F9`) con borde sutil (`#E2E8F0`) detrás del teléfono.
- Sombras suaves.
- Color primario `#2C4EC3` solo en detalles puntuales: palabra clave del título y una línea corta decorativa.
- Logo Agendaza + nombre arriba, centrado.
- Logo de estonianport chico, centrado al pie.

---

## Tipografías

| Uso | Tipografía | Peso |
|---|---|---|
| Logo "AGENDAZA", títulos y subtítulos | **Plus Jakarta Sans** | ExtraBold (títulos), Medium (subtítulos) |
| Nombre "Estonian Port" | **Nunito Sans** | Bold |


---

## Paleta de colores

| Nombre | Hex | Uso |
|---|---|---|
| Primary (cobalto) | `#2C4EC3` | Botones, acentos, palabra clave de los títulos |
| Cobalto oscuro | `#1F3A99` | Detalles |
| Cobalto suave | `#EAEFFC` | Fondos de detalle suaves |
| Texto y fondos oscuros | `#0F172A` | Títulos, textos principales, marco del teléfono |
| Pizarra | `#475569` | Subtítulos y textos secundarios |
| Fondos | `#F8FAFC` | Fondo general de la app |
| Bloques | `#F1F5F9` | Recuadros grises |
| Bordes | `#E2E8F0` | Bordes y divisores |
| Blanco | `#FFFFFF` | Fondo de las imágenes de publicación |

---

## Logos

| Archivo | Descripción |
|---|---|
| `adaptive-icon.png` | Logo de Agendaza: la letra "A" (1024 × 1024 px). |
| `logo.png` | Logo de estonianport: barco en color pizarra (300 × 300 px). |

---

## Versiones

| Versión | Estado | Notas |
|---|---|---|
| 0.1.0 | ✅  | Creacion de proyecto|
| 0.1.1 | ✅  | Ajustes visuales para quitar fondos y iconos extra |
| 0.1.2 | ✅  | Diseño mas sobrio y natural|

Agregá una fila por cada versión nueva y anotá qué cambió en las imágenes (textos, capturas, colores).