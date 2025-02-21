---
title: Темный режим
icon: contrast
order: 1
category:
  - Интерфейс
tag:
  - Темный режим
  - Интерфейс
---

В темном режиме страница использует темный фон, чтобы вам было удобно.

<!-- more -->

## Попробуй это

Нажмите кнопку ниже, чтобы увидеть эффекты.

<!-- markdownlint-disable-->

<AppearanceSwitch />

<!-- markdownlint-restore -->

## Опции

Вы можете настроить темный режим через `darkmode` в настройках темы.

Доступные Варианты:

- `"switch"`: переключение между темным, светлым и автоматическим режимом (по умолчанию)
- `"toggle"`: переключение между светлым и темным режимами
- `"auto"`: автоматически решать, применять ли темный режим на основе цветовой схемы пользовательского устройства или текущего времени
- `"enable"`: только темный режим
- `"disable"`: отключить темный режим

## Глобальные переменные

`$isDarkMode` доступен во всех маркдаун файлах.

<script setup lang="ts">
import AppearanceSwitch from "@theme-hope/modules/outlook/components/AppearanceSwitch.js"
</script>
