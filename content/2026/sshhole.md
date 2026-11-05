---
title: SSH Hole
date: 2026-11-05
categories: IT
tags: 
  - musl
  - openssh
  - Уязвимость
---

https://sshhole.com/

Вот уже долгих 15 лет `musl` из состава `alpine-linux` и `openssh` пропускает отключенного пользователя `root` с любым паролем длиннее 256 символов.