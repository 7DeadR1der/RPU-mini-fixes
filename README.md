# RPU-mini-fixes
This archive contains a couple of fixes for the RPU mods `rpu_rifle_animations.dat` and `rpu_wakizashi_animations.dat`. 
https://github.com/BGforgeNet/Fallout2_Restoration_Project

## EN
### Description

1) Fixed the "Black" character type. Fixed behavior with modified animations for Sniper Rifles and Katanas (wakizashi). The original simply doesn't have animations for these mods.
> Made by copying the default rifle and knife animations.
2) The "KhanRifleFix_default" mod fixes the Khan NPC with a hunting rifle on the 3rd floor of Vault 15. When the `rpu_rifle_animations.dat` mod is disabled, this Khan becomes invisible (due to incorrect default animations). This is only necessary when the new rifle animations mod is DISABLED.
> The mod adds animations like `hmlthrp*.frm` to make this Khan visible again.
3) The "RifleAndWakiFix" mod fixes incorrect animations.
- The original version has an incorrect burst fire animation with the new rifles for the brunette girl in leather armor; a man shoots instead of the girl.
(It actually exists, but for some reason it fixes the animation for the standard rifles.)
> Added file `hflthrpk.frm` (copied from `hflthrjk.frm`)
- Corrected the idle animation for the brunette girl in metal armor with a wakizashi. (originally combat armor animation is used.)
> Added file `hfmetlqa.frm` (copied from hfmetlda.frm) I couldn't find the original idle animation with the wakizashi, so I had to use the knife animation.

### Installation
1) Download zip file https://github.com/7DeadR1der/RPU-mini-fixes/releases/download/fix/mini-fixes.zip

1) Simply copy the corrected "Black" character type to "appearance/" and replace it.

2) Copy the "KhanRifleFix_default" mod to "mods/." And add it to the folder name in "mods_order.txt." (Again, this is only possible if you disabled the `rpu_rifle_animations.dat` mod; otherwise, this is pointless.)

3) Copy the "RifleAndWakiFix" mod to "mods/" and add it to the folder name in "mods_order.txt." Important: the "RifleAndWakiFix" mod must appear **after(!)** `rpu_rifle_animations.dat` and `rpu_wakizashi_animations.dat`


## RU
### Описание

1) Исправлен тип персонажа «Черный». Исправлено поведение с измененными анимациями для снайперских винтовок и катан (вакидзаси). В оригинале просто нет анимаций для этих модов.
> Сделано путем копирования стандартных анимаций винтовки и ножа.

2) Мод «KhanRifleFix_default» исправляет NPC Хана с охотничьей винтовкой на 3-м этаже Убежища 15. Когда мод `rpu_rifle_animations.dat` отключен, этот Хан становится невидимым (из-за некорректных стандартных анимаций). Это необходимо только тогда, когда мод с новыми анимациями винтовки ОТКЛЮЧЕН.
> Мод добавляет анимации, такие как `hmlthrp*.frm`, чтобы сделать этого Хана снова видимым.

3) Мод «RifleAndWakiFix» исправляет некорректные анимации.
- В оригинальной версии у девушки-брюнетки в кожаной броне некорректная анимация стрельбы очередями с новыми винтовками; стреляет мужчина вместо девушки.
(На самом деле она существует, но по какой-то причине исправляет анимацию для стандартных винтовок.)
> Добавлен файл `hflthrpk.frm` (скопирован из `hflthrjk.frm`)
- Исправлена ​​анимация бездействия у девушки-брюнетки в металлической броне с вакидзаси. (Изначально используется анимация боевой брони.)
> Добавлен файл `hfmetlqa.frm` (скопирован из hfmetlda.frm) Я не смог найти оригинальную анимацию бездействия с вакидзаси, поэтому пришлось использовать анимацию ножа.

### Установка
1) Скачайте zip-файл https://github.com/7DeadR1der/RPU-mini-fixes/releases/download/fix/mini-fixes.zip

1) Просто скопируйте исправленный тип персонажа "Black" в папку "appearance/" и замените им существующий.

2) Скопируйте мод "KhanRifleFix_default" в папку "mods/". И добавьте его в папку с именем в файле "mods_order.txt". (Опять же, это возможно только если вы отключили мод `rpu_rifle_animations.dat`; в противном случае это бессмысленно.)

3) Скопируйте мод "RifleAndWakiFix" в папку "mods/" и добавьте его в папку с именем в файле "mods_order.txt". Важно: мод "RifleAndWakiFix" должен располагаться **после (!)** файлов `rpu_rifle_animations.dat` и `rpu_wakizashi_animations.dat`.
