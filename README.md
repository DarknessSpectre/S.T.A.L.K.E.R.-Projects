Мои проекты:

| Релиз | Описание | Скачивание |
| --- | --- | --- |
| **Тень Чернобыля — OGSR Edition** | Проект изначально создавался для личного использования. Его цель — сохранить дух оригинала, исправить основные ошибки и недочёты и сделать прохождение удобнее. Современный движок сочетается с исправлениями заданий, диалогов и поведения NPC, обновлённой оружейной частью и отдельными механиками из последующих игр серии. Визуальные изменения остаются сдержанными, с сохранением узнаваемого облика «Тени Чернобыля». [Подробное описание изменений](CHANGES.md). | [Скачать](https://github.com/DarknessSpectre/S.T.A.L.K.E.R.-Projects/releases/tag/1.0) |
| **Путь во мгле — OGSR CoP Standalone** | Автономная адаптация «Пути во мгле» на базе OGSR. В релиз включено всё необходимое для запуска: достаточно распаковать архив. | [Скачать адаптацию](https://github.com/DarknessSpectre/OGSR-Engine-WoT-SP-Fixes/releases/tag/3.597_CoP_SP_S) |
| **OGSR Engine — WoT & SP Fixes** | Общая сборка движка для адаптаций Wind of Time и Spectrum Project на базе официальной ветки OGSR для «Зова Припяти». Исправлено отображение русских названий звуковых устройств, добавлены подсветка совместимых скриптовых обвесов и физические защиты в карточке артефакта. Исправлено чтение сохранённого состояния машин, включая сюжетный БТР Spectrum Project. | [Скачать движок и комплектные ресурсы](https://github.com/DarknessSpectre/OGSR-Engine-WoT-SP-Fixes/releases/tag/3.597_CoP_WoT_SP) |
| **Путь во мгле 1.07 — пакет адаптации для OGSR** | Адаптация для самостоятельной установки на «S.T.A.L.K.E.R.: Зов Припяти» 1.6.02 и gamedata Spectrum Project 1.07. В релизе приведён порядок установки и запуска через лаунчер или start.bat. | [Скачать пакет адаптации](https://github.com/DarknessSpectre/OGSR-Engine-WoT-SP-Fixes/releases/tag/3.597_CoP_SP_A) |
| **Ветер времени — исправления адаптации OGSR CoP** | Набор исправлений для «Ветра времени»: устранение вылетов телепорта и диалогов, исправления интерфейса, карты, ПНВ и логики персонажей. Переработано сопровождение отряда Макса на Радаре. Дополнительно доступна правка возврата отобранных денег в заданиях «Странный схрон» и «Возмездие». | [Скачать исправления](https://github.com/DarknessSpectre/OGSR-Engine-WoT-SP-Fixes/releases/tag/3.597_CoP_WoT) |
| **SquashFS 7z Plugin** | Плагин для работы с архивами OGSR `.sq` и `.sq_01` прямо в 7-Zip. Поддерживает просмотр, распаковку, создание и редактирование архивов SquashFS 4.0 со сжатием LZ4. Позволяет добавлять, заменять, переименовывать и удалять файлы; учитывает структуру `gamedata` и кодировку имён CP1251 при упаковке для OGSR. | [Страница проекта и установка](https://github.com/DarknessSpectre/ogsr-squashfs-7z-plugin) |

#  S.T.A.L.K.E.R.: Тень Чернобыля — OGSR Edition

В сборке модификации разделены на пакеты с определённым порядком загрузки. Их состав и работа описаны в [данном файле](CHANGES.md)

| Компонент | Использование в сборке |
| --- | --- |
| [OGSR Engine](https://github.com/OGSR/OGSR-Engine) | Движок игры. |
| [Неофициальный патч 1.0007 от lvg_brest](https://ap-pro.ru/forums/topic/1764-neoficialnye-patchi-10007-i-1511-ot-lvg_brest/) | Пакет исправлений и наработок, выборочно адаптированный под сборку. |
| [OWR 3.0](https://ap-pro.ru/forums/topic/1832-owr/) | Оружейный пакет, переработанный для OGSR и системы сменных рук. |
| [ABC — Sleeping Bag Mod](https://www.moddb.com/mods/abc-sleeping-bag-mod) | Основа механики сна. |
| [ITS Repair Mod — New UI](https://www.playground.ru/stalker_shadow_of_chernobyl/file/s_t_a_l_k_e_r_shadow_of_chernobyl_its_repair_mod_new_ui-1833499) | Основа ремонта снаряжения. |
| [Arena Extension Mod 0.3.2](https://www.playground.ru/stalker_shadow_of_chernobyl/file/s_t_a_l_k_e_r_shadow_of_chernobyl_arena_extension_mod_ver_0_3_2-861186) | Расширение арены. |
| [Atmospherics](https://drive.google.com/file/d/1wwzxPmJNXStUDelBtzaOUDWOmIn7dDjh/view) | Погодный пакет в адаптации для OGSR. |
| [Vanilla Textures Overhaul](https://www.moddb.com/games/stalker/addons/stalker-shadow-of-chernobyl-vanilla-textures-overhaul) | Обновлённые текстуры. |
| [H8 ClassicPack 2.1](https://www.moddb.com/games/stalker/addons/h8-classic-pack-npc-models) | Модели NPC. |
| [«Повелитель Зоны» Gold 5.0](https://ap-pro.ru/forums/topic/3487-povelitel-zony-gold-50-dlya-tch/) | Спавнер и инструменты тестирования. |


Часть компонентов переработана для совместной работы в сборке. Благодарность авторам оригинальных модификаций и команде OGSR за их работу.
