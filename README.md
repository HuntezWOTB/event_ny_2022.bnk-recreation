# event_ny_2022.bnk recreation

Цель данного проекта - замена и улучшение звуков новогоднего ангара 2021-2022 в игре World of Tanks Blitz

Как это использовать:
1) Скачиваем WWISE Launcher из официального сайта аудиодвижка  
2) Устанавливаем WWISE Launcher  
3) Запускаем WWISE Launcher  
4) В WWISE Launcher выбираем пункт WWISE (второй с левого ряда)  
5) В пункте INSTALL NEW VERSION из пункта Latest выбираем пункт All  
6) Справа от All меняем 2021.1 на 2019.2  
7) Справа от 2019.2 выбираем версию WWISE 2019.2.9.7459  
8) После выбранной версии нажимаем снизу на кнопку Install...  
9) После установки открываем Загрузки в Проводнике  
10) Распаковываем WWISE VOICE WOT BLITZ проект полностью (лучше в удобное место)  
11) Открываем двумя быстрыми кликами файл WOTB_WWISE_VOICE.wproj  
12) После открытия открываем пункт Audio  
и открываем Actor-Mixer Hierarchy  
Дальше открываем Default Work Unit; Events; NY_2022

И редактируем то, что вам нужно


Если хотите поставить свою музыку в ангаре:
1) Убираем все галочки у квадратиков в Default Work Unit; Events; NY_2022 у аудиофайлов (кроме melody_BPM63)
2) Переименовываем свой аудиофайл в формате .wav в melody_BPM63
3) Заменяем melody_BPM63 на свой melody_BPM63 (зажав файл и наложив его поверх melody_BPM63 в wwise)
4) Подтверждаем замену аудиофайла
5) Заходим в SoundBanks
6) Правой кнопкой мыши нажимаем на Default Work Unit
7) Выбираем Generate Soundbank(s) for current platform
8) После генерации закрываем окно с успешной операцией и заходим в папку с проектом
9) В папке с проектом открываем папку GeneratedSoundBanks, затем Windows
10) event_ny_2022.bnk преобразуем в формат .dvpl
11) event_ny_2022.bnk.dvpl копируем в папку World of Tanks Blitz\Data\WwiseSound
12) Подтверждаем замену файлов
 Поздравляем, мод на Steam установлен!
 
 Для андроид:
 11.1) Включаем в настройках игры "Загрузить все ресурсы игры"
 11.2) event_ny_2022.bnk.dvpl копируем в папку Android\data\net.wargaming.wot.blitz\files\packs\WwiseSound
 11.3) Подтверждаем замену файлов
  Мод на андроид установлен!
