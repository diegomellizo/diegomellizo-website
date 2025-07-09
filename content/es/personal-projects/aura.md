---
title: "Aura: Master of the Elements"
subtitle: "Proyecto de curso de Udemy"
devDate: "2023 - 2025"
cardImage: "/shared-l10n/personal-projects/card-images/aura.jpg"
weight: 3
---

#### 2023 - 2025
\
{{< video-js src="/shared-l10n/personal-projects/videos/aura.mp4" autoplay=false preload=false >}}

{{< icons/icon vendor=mdi name=gamepad-variant >}} Descargar desde [itch.io](https://mellizogames.itch.io/aura)

{{< icons/icon vendor=mdi name=puzzle >}} **Género:** *RPG* (*Role-Playing Game*; juego de rol), vista desde arriba 3D.\
{{< icons/icon vendor=mdi name=information >}} **Descripción:**
Proyecto completado para el curso de Udemy: *Unreal Engine 5 - Gameplay Ability System - Top Down RPG*, por Stephen Ulibarri.

{{< icons/icon vendor=mdi name=hammer-wrench >}} **Desarrollado con:** Unreal Engine (C++ y *Blueprint* \[sistema de programación visual]).\
{{< icons/icon vendor=mdi name=target >}} **Plataforma objetivo:** PC Windows.

{{< icons/icon vendor=mdi name=hand-heart >}} **Mi contribución:**
* Varias correcciones de errores y mejoras en todo el proyecto.
* Diseño y construcción de dos niveles de mazmorra utilizando los *assets* (recursos) modulares proporcionados y objetos interactivos desarrollados a lo largo del curso, p. ej. generadores de enemigos y puntos de control.
* Balanceo del juego, incluyendo el ajuste de valores como:
  * Salud y maná de los personajes.
  * Daño, costo de maná, *cooldown* (tiempo de reutilización) y requisito de nivel de las habilidades.
  * Cantidad de salud/maná restaurados y probabilidad de aparición de *pickups* (recogibles).
  * Progresión de nivel del jugador.
* Implementación del objetivo del juego, incluyendo:
  * Pantallas de intro/outro con fragmentos narrativos, que se muestran al comienzo/final del juego respectivamente.
  * Popup de intro con objetivo del juego, que se muestra después de la pantalla de intro.
  * Adición de balizas encontradas a un contador total.
  * Apertura del portal de un nivel de mazmorra al siguiente después de encontrar todas las balizas.
  * Cinemática final.
* Otras adiciones son:
  * *Splash screen* (pantalla de presentación) e icono del juego.
  * Música del juego.
  * Menú de pausa con:
    * Opción para ajustar la calidad del juego (autoguardada).
    * Opción para ajustar el volumen de la música (autoguardado).
    * Panel que muestra los controles del juego.
  * El nombre del nivel de mazmorra se muestra al entrar.
  * Se muestra un mensaje después de encontrar un punto de control o baliza.
  * El nivel de los enemigos se muestra sobre su barra de salud.
  * Guardado y carga de enemigos (adición al sistema ya existente de guardado del juego).
  * Cuenta regresiva de reaparición del jugador.
