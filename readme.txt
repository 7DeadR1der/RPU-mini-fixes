ru and en description

===== RU =====
Данный архив содержит пару фиксов для RPU.

Описание

1) Исправленный типаж "Black". Исправлено поведение с измененными анимациями Снайперских винтовок и Катан (wakizashi). В оригинале просто нет анимаций для этих модов
p.s. Сделано путем копирования стандартных анимаций винтовок и ножей
2) мод "KhanRifleFix_default" исправляет NPC Хана с охотничьей винтовкой, на 3 этаже убежища 15. При отключенном моде "rpu_rifle_animations.dat", этот Хан становится невидимым (из-за неверной анимации по умолчанию). Необходим только при ОТКЛЮЧЕННОМ моде на новые анимации винтовок
p.s. мод добавляет анимации типа hmlthrp*.frm чтобы этот хан снова отображался.
3) мод "RifleAndWakiFix" исправляет некорректные анимации. 
В оригинале неверная анимации burst fire с новыми винтовками для девушки брюнетки в кожаной броне, вместо девушки стреляет мужик. 
(Вообще она есть, но почему-то она исправляет анимацию стандартных винтовок) 
p.s. добавляется файл hflthrpk.frm (скопирован с hflthrjk.frm)

Исправляется анимация бездействия для девушки брюнетки в металлической броне с вакидзаси. (используется анимация боевой брони)
p.s. добавляется файл hfmetlqa.frm (скопирован с hfmetlda.frm) Я не смог найти оринальную анимацию idle с вакидзаси, поэтому пришлось использовать анимацию с ножом

Установка

1)исправленный типаж "Black" просто копируете в "appearance/" с заменой

2) мод "KhanRifleFix_default" копируете в "mods/". И добавляете в название папки в "mods_order.txt" (Опять же, если вы отключили мод "rpu_rifle_animations.dat", иначе это бессмысленно)

3) мод "RifleAndWakiFix" копируете в "mods/". И добавляете в название папки в "mods_order.txt". Важно мод "RifleAndWakiFix" должен стоять после(!) "rpu_rifle_animations.dat" и "rpu_wakizashi_animations.dat"



===== EN =====
This archive contains a couple of fixes for the RPU.

Description

1) Fixed the "Black" character type. Fixed behavior with modified animations for Sniper Rifles and Katanas (wakizashi). The original simply doesn't have animations for these mods.
p.s. Made by copying the default rifle and knife animations.
2) The "KhanRifleFix_default" mod fixes the Khan NPC with a hunting rifle on the 3rd floor of Vault 15. When the "rpu_rifle_animations.dat" mod is disabled, this Khan becomes invisible (due to incorrect default animations). This is only necessary when the new rifle animations mod is DISABLED.
p.s. The mod adds animations like hmlthrp*.frm to make this Khan visible again.
3) The "RifleAndWakiFix" mod fixes incorrect animations.
The original version has an incorrect burst fire animation with the new rifles for the brunette girl in leather armor; a man shoots instead of the girl.
(It actually exists, but for some reason it fixes the animation for the standard rifles.)
P.S. Added file hflthrpk.frm (copied from hflthrjk.frm)

Corrected the idle animation for the brunette girl in metal armor with a wakizashi. (The combat armor animation is used.)
P.S. Added file hfmetlqa.frm (copied from hfmetlda.frm) I couldn't find the original idle animation with the wakizashi, so I had to use the knife animation.

Installation

1) Simply copy the corrected "Black" character type to "appearance/" and replace it.

2) Copy the "KhanRifleFix_default" mod to "mods/." And add it to the folder name in "mods_order.txt." (Again, this is only possible if you disabled the "rpu_rifle_animations.dat" mod; otherwise, this is pointless.)

3) Copy the "RifleAndWakiFix" mod to "mods/" and add it to the folder name in "mods_order.txt." Important: the "RifleAndWakiFix" mod must appear after (!) "rpu_rifle_animations.dat" and "rpu_wakizashi_animations.dat."