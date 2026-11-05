---
title: SSH hole
date: 2026-11-05
categories: IT
tags: 
  - musl
  - openssh
  - Уязвимость
---

https://sshhole.com/
Долгих 30 лет `alpine-linux` + `openssh` пропускали ОТКЛЮЧЕННОГО (!) пользователя `root` (!!) с ЛЮБЫМ (!!!) паролем больше 256 символов. И, кажется, делает это до сих пор.

Уму непостижимо!