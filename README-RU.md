## Godot Engine 2.1.5 ToolSet
Packaged by: Chimbal (https://github.com/Shedou, https://overclockers.ru/blog/Hard-Workshop)

Language: ([EN](https://github.com/Shedou/godot-engine-toolset-v215) / RU)

Скачать: [Godot Engine ToolSet v2.1.5](https://github.com/Shedou/godot-engine-toolset-v215/releases/tag/first)

Автономный комплект разработки для проектов на основе Godot Engine версии 2.1.5.

## Состав набора:
- Godot Engine - Официальная версия + неофициальная версия + исходный код.
- Export Templates - Официальные шаблоны экспорта + неофициальные для поддержки Windows XP.
- Rcedit v1.1.1 (Windows XP+) / v2.0.0 - Утилита для изменения значка при экспорте (Windows).
- Mesa - Позволяет использовать ЦП вместо видеокарты для работы OpenGL API. Помогает с запуском в виртуальной машине без 3D ускорения.
- Start-Editor-* - Скрипты для запуска редактора в портативном режиме. Домашний каталог переносится в папку UserData.

## Шаблоны экспорта:
- Шаблоны экспорта находяться в каталоге Templates.
- Официальные шаблоны (Templates-Official) несовместимы с Windows XP!
- Для совместимости с Windows XP следует использовать шаблоны из папки Templates-XP.

1) Если предполагается работа с переносом домашнего каталога в папку UserData, запуская редактор через скрипты Start-Editor-*, то копировать файлы шаблонов экспорта нужно в следующие каталоги:
> Windows - UserData\Windows\AppData\Roaming\Godot\templates\
> Linux - UserData/Linux/.godot/templates/

2) Если запускать редактор Godot Engine напрямую из каталога Editor, то шаблоны экспорта следует копировать в следующие каталоги:
> Windows - C:\Users\ИМЯ_ПОЛЬЗОВАТЕЛЯ\AppData\Roaming\Godot\templates\
> Linux - /home/ИМЯ_ПОЛЬЗОВАТЕЛЯ/.godot/templates/

## Mesa:
- Данная библиотека позволяет запускать Godot Engine и прочие программы, используя центральный процессор вместо видеокарты.
- Работает только с OpenGL API в среде Windows.
- Для использования скопировать opengl32.dll в каталог с программой (где "*.exe").
- ВАЖНО! 32-битная версия программы (игры) будет работать только с 32-битной Mesa! При запуске 64-битной программы с 32-битной Mesa будет ошибка!

## Совместимость набора:
- Godot Engine (Редактор): Windows 7+ | Linux (glibc 2.17+), Debian 8+
- Шаблоны экспорта (официально): Windows 7+ | Linux (glibc 2.15+), Debian 8+
- Шаблоны экспорта (неофициально): Windows XP+

## Примечания:
- Неофициальный редактор может работать некорректно в среде Windows XP.


## Проекты включенные в набор:

- Godot-2.1.5 Official:
> https://github.com/godotengine/godot
> 
> https://github.com/godotengine/godot/releases/tag/2.1.5-stable

- Godot-2.1.5-Windows-XP:
> https://github.com/DNS/Godot-2.1.5-Windows-XP

- Rcedit:
> https://github.com/electron/rcedit

- Mesa:
> http://mesa.fdossena.com
> 
> https://downloads.fdossena.com/Projects/Mesa3D
