## 🪄 Harry Potter: Duelo de Hechizos en Python

¡Bienvenido al Callejón Diagon! Este es un juego de rol por turnos desarrollado en Python donde dos magos se enfrentan en un duelo épico utilizando hechizos de ataque y defensa. ¿Serás un gran mago o un simple muggle?

## 🎮 Descripción del Juego

El programa simula un combate entre dos jugadores. Cada turno, podrás decidir si lanzar un hechizo ofensivo para restar vida a tu oponente o un hechizo defensivo para recuperar la tuya. El duelo termina cuando la vida de uno de los magos llega a cero.

## ✨ Características principales:

Sistema de Turnos: Jugador 1 y Jugador 2 se turnan para actuar.

Hechizos Aleatorios: Los nombres de los hechizos se seleccionan al azar de una lista predefinida.

Daño y Curación Dinámica: Se utiliza el módulo random para generar valores variables en cada acción.

Ambientación: Mensajes personalizados con temática del mundo mágico.

## 🛠️ Requisitos
Python 3.x instalado.

No requiere librerías externas (solo utiliza el módulo nativo random).

 ## 🚀 Cómo jugar
Clona o descarga el archivo .py en tu ordenador.

Ejecuta el script desde tu terminal o IDE:

Bash
python nombre_de_tu_archivo.py

Sigue las instrucciones en pantalla:

Pulsa A para lanzar un Ataque.

Pulsa D para lanzar una Defensa.

Pulsa S si quieres abandonar el duelo como un cobarde (Salir).

## 📜 Mecánicas del CombateAcciónEfectoAtacar 

(A)Lanza un hechizo ofensivo que resta entre 1 y 50 puntos de vida al rival.
Defender (D)Lanza un hechizo de curación que suma entre 1 y 50 puntos a tu vida.
Salir (S)Finaliza la ejecución del programa inmediatamente.

## 📂 Estructura del Código
El código utiliza:

while True: Para mantener el flujo del juego activo hasta que haya un ganador.

if/elif/else: Para gestionar la lógica de los turnos y las decisiones de los jugadores.

random.randint() y random.choice(): Para dar variedad a los efectos y nombres de los hechizos.

## ⚡ Próximas mejoras (To-Do)
[ ] Añadir una base de datos de hechizos más amplia.

[ ] Implementar un sistema de "Maná" o energía limitada.

[ ] Crear un modo de juego contra la IA (Voldemort).

[ ] Añadir efectos de sonido o interfaz gráfica.

"No son nuestras habilidades las que muestran lo que somos, sino nuestras elecciones."
— Albus Dumbledore

## 👥 Equipo de Magos (Créditos)

Este proyecto fue posible gracias a la colaboración y el trabajo en equipo de este grupo de talentosas magas:

*   ✨ **[Fabiola Hernández Lorenzo]** - "Experta en Pociones de Código" encuentrala en : 

📧 Email: fabihernandez96@gmail.com 

🐙 GitHub: fabihrndz

💼 LinkedIn : //www.linkedin.com/in/fabiola-hernández-lorenzo-6b7554162?utm_source=share_via&utm_content=profile&utm_medium=member_android

*   ✨ **[Laura Mulero Sequera]** - "Experta en Pociones de Código" encuentrala en : 

📧 Email: sequeralaura@gmail.com 

🐙 GitHub: laura-23-code 

💼  LinkedIn www.linkedin.com/in/lauramulero

*   ✨ **[Valeria Angélica Mora Salcedo]** - "Especialista en Encantamientos" encuentrala en : 

📧 Email:valeangie.mora@gmail.com

🐙 GitHub : valeangie 

💼 LinkedIn :  https://www.linkedin.com/in/valeriamoras?utm_source=share_via&utm_content=profile&utm_medium=member_ios

*   ✨ **[Sara Guzman Lopez]** - "Maestra de Lógica de Duelos" encuentrala en:

📧 Email: saraguzmanlopez@gmail.com

🐙 GitHub: saraguzmanlopez-ops

💼 LinkedIn:https://www.linkedin.com/in/sara-guzman-lopez/
---

### 🤝 Contribuciones
Si quieres colaborar con nosotras o sugerir nuevos hechizos, ¡siéntete libre de abrir un *Pull Request* o enviarnos un búho mensajero!