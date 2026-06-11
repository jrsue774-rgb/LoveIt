---
weight: 5
title: "Personaliza tu Terminal en Linux"
date: 2026-06-11T10:00:00-04:00
lastmod: 2026-06-11T10:00:00-04:00
draft: false
author: "jrsue774-rbg"
authorLink: "https://github.com/jrsue774-rbg"
description: "Cambia colores, fuentes y el prompt de tu terminal para que sea tuya de verdad."
images: []
resources:
- name: "featured-image"
  src: "featured-image.jpg"

tags: ["linux", "terminal", "bash"]
categories: ["Linux"]

twemoji: false
lightgallery: true
---

Después de aprender los comandos básicos, el siguiente paso natural es hacer que tu terminal se sienta como tuya.

<!--more-->

Pasar horas en una terminal genérica aburre. La buena noticia es que personalizarla no toma mucho tiempo y la diferencia es enorme.

## Cambia el prompt (PS1)

El prompt es lo que aparece antes de cada comando. Puedes editarlo en tu archivo ~/.bashrc:

```bash
PS1='\[\e[1;32m\]\u@\h\[\e[0m\]:\[\e[1;34m\]\w\[\e[0m\]\$ '