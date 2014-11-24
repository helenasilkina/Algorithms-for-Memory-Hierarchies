Иерархия памяти — термин, используемый в вычислительной технике при проектировании и программировании ЭВМ (компьютеров). Означает, что различные виды памяти образуют иерархию, на различных уровнях которой расположены памяти с отличающимися временем доступа, сложностью, стоимостью и объемом. Возможность построения иерархии памяти вызвана тем, что большинство алгоритмов обращаются в каждый промежуток времени к небольшому набору данных, который может быть помещен в более быструю, но дорогую и поэтому небольшую, память (см. en:locality of reference). Использование более быстрой памяти увеличивает производительность вычислительного комплекса. Под памятью в данном случае подразумевается устройство хранения данных (запоминающее устройство) в Вычислительной технике или компьютерная память.

При проектировании высокопроизводительных компьютеров и систем необходимо решить множество компромиссов, например, размеры и технологии для каждого уровня иерархии. Можно рассматривать набор различных памятей (m1,m2,…,mn), находящихся в иерархии, то есть каждый mi уровень является как бы подчиненным для mi-1 уровня иерархии. Для уменьшения времени ожидания на более высоких уровнях, низшие уровни могут подготавливать данные укрупненными частями с буферизацией и, по наполнению буфера, сигнализировать верхнему уровню о возможности получения данных.

Часто выделяют 4 основных (укрупненных) уровня иерархии:
    Внутренняя память процессора (регистры, организованные в регистровый файл и кэш процессора).
    ОЗУ системы (RAM) и вспомогательных карт памяти.
    Накопители с «горячим» доступом (On-line mass storage) — или вторичная компьютерная память. Жесткие диски и твердотельные   накопители, не требующие длительных (секунды и больше) действий для начала получения данных
    Накопители, требующие переключения носителей (Off-line bulk storage) — или третичная память. Сюда относятся магнитные ленты, ленточные и дисковые библиотеки, требующие длительной перемотки либо механического (или ручного) переключения носителей информации.
