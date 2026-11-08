# El pozo del eco

Un pequeño personaje cae a un pozo. Sobrevive al golpe, pero levantarse es solo el principio.

**El pozo del eco** es un prototipo de acción y plataformas de Random Games, pensado para jugar en horizontal desde el celular. Explora ruinas oscuras, trepa por sus bordes y encuentra una salida entre orugas y un jefe.

> Proyecto en desarrollo. Los niveles, las animaciones y los controles todavía están cambiando.

## El personaje

Los dibujos del protagonista fueron creados por el autor del proyecto. Estas son algunas de sus poses reales, no capturas del escenario:

| Reposo | Caminar |
|---|---|
| ![Personaje en reposo](assets/personaje-idle.png) | ![Cuadro de caminar](assets/personaje-caminar.png) |

| Ataque | Después de la caída |
|---|---|
| ![Cuadro de ataque](assets/personaje-ataque.png) | ![Personaje inconsciente](assets/personaje-caido.png) |

## Qué puedes hacer

- Moverte, saltar y correr con controles táctiles.
- Trepar automáticamente al acercarte a un borde mientras avanzas hacia él.
- Mantener el botón de apuntar para quedarte quieto y atacar; el joystick dirige los golpes a los lados o hacia arriba.
- Enfrentarte a orugas y a un jefe.
- Ver una introducción distinta en cada nivel.
- Al morir, ver una repetición muy rápida en reversa antes de reiniciar.
- Crear escenarios en el editor integrado, con una paleta de 40 opciones y triggers para desplazar plataformas.
- Guardar y cargar niveles en JSON.

## Cómo probarlo

Descarga **Random-Games-Prototipo.html** desde este repositorio y ábrelo con un navegador actualizado. Coloca el celular en horizontal y toca la pantalla para habilitar el audio.

La música y los dibujos están incluidos en el HTML. El prototipo no necesita cámara y todavía no es una APK.

## Curiosidades

- El personaje empezó como una pildorita provisional, antes de recibir sus dibujos actuales.
- El idle tiene un ritmo poco habitual: sus cuatro cuadros duran **10, 6, 2 y 6 segundos**, en ese orden. Un ciclo completo dura 24 segundos.
- Las animaciones se voltean para cambiar de dirección, evitando dibujar una segunda versión de cada secuencia.
- La trepada originalmente pedía pulsar salto otra vez. Se volvió automática para hacerla más cómoda en celular.
- La secuencia del pozo usa **11 cuadros**: tres de caída, tres de impacto y cinco para levantarse.
- El terreno tuvo una versión con bloques de césped antes de cambiar a ruinas oscuras.
- La iluminación está hecha con capas, gradientes y transparencias en Canvas, no con shaders reales.
- Hollow Knight y Silksong son referencias de atmósfera y exploración; los dibujos del personaje y el escenario de este proyecto no son recursos extraídos de esos juegos.

## Música y créditos

- **Cave Theme — Brandon Morris (HaelDB / Brandon75689)**. Opción de licencia utilizada: CC0. [Fuente](https://opengameart.org/content/cave-theme).
- **Loopable Dungeon Ambience — JaggedStone**. CC0. [Fuente](https://opengameart.org/content/loopable-dungeon-ambience).
- **RPG – The Cave (Ambient) — HitCtrl**. [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). [Fuente](https://opengameart.org/content/rpg-the-cave-ambient). Audio integrado sin modificar.

Las licencias de esas pistas no otorgan una licencia sobre el resto del proyecto. La licencia del código y de los dibujos propios aún está por definir.
