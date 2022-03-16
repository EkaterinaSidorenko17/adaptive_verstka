﻿# adaptive_verstka
# Условия медиазапросов (@media)

##Тип устройства:
###all 	Подходит для всех типов устройств.
###print 	Предназначен для страничных материалов и документов, просматриваемых на экране в режиме предварительного просмотра печати.
###screen 	Предназначен в первую очередь для экранов цветных компьютерных мониторов.
###speech 	Предназначен для синтезаторов речи.

Характеристики устройства:
###width 	 - Проверяет ширину области просмотра. Значения задаются в единицах длины, px, em и т.д., например, (width: 800px). Обычно для проверки используются минимальные и максимальные значения ширины.
###min-width - применяет правило если ширина области просмотра больше значения, указанного в запросе, max-width — ширина области просмотра меньше значения, указанного в запросе.
###height 	 - Проверяет высоту области просмотра. Значения задаются в единицах длины, px, em и т.д., например, (height: 500px). Обычно для проверки используются минимальные и максимальные значения высоты.
###min-height - применяет правило если высота области просмотра больше значения, указанного в запросе, max-height — высота области просмотра которого меньше значения, указанного в запросе.
###aspect-ratio 	- Проверяет соотношение ширины к высоте области просмотра. Широкоэкранный дисплей с соотношением сторон 16:9 может быть помечен как (aspect-ratio: 16/9).
###min-aspect-ratio - проверяет минимальное соотношение, max-aspect-ratio — максимальное соотношение ширины к высоте области просмотра.
###orientation 	- Проверяет ориентацию области просмотра. Принимает два значения: (orientation: portrait) и (orientation: landscape).
###resolution 	- Проверяет разрешение экрана (количество пикселей). Значения также могут проверять количество точек на дюйм (dpi) или количество точек на сантиметр (dpcm), например, (resolution: 300dpi).
###min-resolution - проверяет минимальное разрешение экрана, max-resolution — максимальное.
###color 	- Проверяет количество бит на каждый из цветовых компонентов устройства вывода. Например, (min-color: 4) означает, что экран конкретного устройства должен иметь 4-битную глубину цвета.
###min-color - проверяет минимальное количество бит, max-color — максимальное количество бит.
###color-index 	- Проверяет количество записей в таблице подстановки цветов. В качестве значения указывается положительное число, например, (color-index: 256).
###min-color-index - проверяет минимальное количество записей, max-color-index — максимальное количество записей.
###monochrome 	- Проверяет количество битов на пиксель монохромного устройства. Значение задается целым положительным числом, например, (min-monochrome: 8).
###min-monochrome - проверяет минимальное количество битов, max-monochrome — максимальное количество битов.
###-webkit-device-pixel-ratio 	- Задаёт количество физических пикселей устройства на каждый CSS-пиксель.
