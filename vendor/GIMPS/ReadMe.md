[License]://creativecommons.org/licenses/by-nc-sa/4.0/deed.ru

Приложение|Редакция|Версия|Дата|Язык
---|---|---|---|---
Prime95 <sup>[www]</sup>|Release|29.4|2018-02-09|en

[www]://mersenne.org/download/ "Download"

### Краткое описание

Официальное приложение проекта GIMPS (Great Internet Mersenne Prime Search) осуществляет поиск простых чисел 
*среди* чисел Мерсенна (2<sup>n</sup>-1). Для поиска требуются современные компьютеры, потому как сложность 
поиска быстро возрастает.

Помимо поиска [простых чисел Мерсенна] используя различные [методы] можно вычислить простые множители 
(сомножители, факторы) чисел Мерсенна. Каждое число Мерсенна имеет очень [мало сомножителей].  
Поиск сомножителей методами [P-1] (алгоритм Полларда) и [ECM]<sup>[*]</sup> (метод случайных эллиптических 
кривых) требует свободной памяти, потому в случае недостатка памяти вычисления остановятся, а в графе `Stage` 
назначенных заданиях появятся *метки* без указания процентов. Зато эти методы находят простые сомножители 
на несколько порядков длиннее.  

Проверка [PRP] (вероятное простое) с большой вероятностью укажет, если простые сомножители (все или с одним 
недостающим) будут найдены; или число Мерсенна не имеет сомножителей и является простым (данный метод заменил 
тест LL). Чем длиннее уже найденные простые сомножители, тем больше шансов успешно пройти проверку PRP.
``` cfg
# Параметры, передаваемые программе
PRP=1,2,{EXPONENT},-1,"{FACTOR_N1},{FACTOR_N2}"
PRP=1,2,{EXPONENT},-1,{BIT_LAST},0,{opt_N_BASE},{opt_N_RESIDUE}
```

Любой метод добавляет очков в проекте GIMPS.

[простых чисел Мерсенна]://www.mersenne.ca/prime.php
[методы]://www.mersenne.org/various/math.php
[мало сомножителей]://www.mersenne.ca/manyfactors.php
[P-1]://www.mersenne.ca/p1missed.php?min=1&max=999999999
[ECM]://www.mersenneforum.org/showthread.php?t=194
[*]://www.mersenneforum.org/showpost.php?p=1406&postcount=19
[PRP]://www.mersenne.ca/prp.php?show=2&min_exponent=1213&max_exponent=4871

---

# Содержание репозитория

- ***FastFactoring*** - таблица #1 найденных простых делителей
- ***TrialFactoring.md*** - таблица #2 найденных простых делителей
- ***ReadMe.md*** - описание и рекомендации по проекту GIMPS

# Дополнительные приложения

### :cyclone: Приложения для поиска простых сомножителей на GPU

1. [gpuOwL] a tiny OpenCL 
2. [mfaktc] a CUDA 
3. [mfakto] an OpenCL 
4. [yafu] 

[gpuOwL]:http://www.mersenneforum.org/showthread.php?t=22204
[mfaktc]:http://www.mersenneforum.org/showthread.php?t=12827
[mfakto]:http://www.mersenneforum.org/showthread.php?t=15646
[yafu]:http://www.mersenneforum.org/showthread.php?p=488202

### :cyclone: Формула пополнения таблицы в Excel

`=СЦЕПИТЬ("|";A1;"|M<sub>";B1;"</sub>|";ТЕКСТ(D1;"ГГГГ-ММ-ДД");"|[";ПОДСТАВИТЬ(ЛЕВСИМВ(F1;ПОИСК(" / ";F1)-1);"Factor: ";"");"](https://mersenne.org/M";B1;" """;ТЕКСТ(LOG(ПОДСТАВИТЬ(ЛЕВСИМВ(F1;ПОИСК(" / ";F1)-1);"Factor: ";"");2);"0,0_ бит");""")")`

На 2018-10-31 найдены 81 сомножителя.

### :cyclone: Ссылки на пояснения и приложения

1. [Простые числа Мерсенна и Тест Люка-Лемера](//habr.com/post/327342/ "RU, 2017-04-25")
2. [Mersenne Prime](//download.mersenne.ca/ "EN")
3. **[factordb.com](//factordb.com/index.php?query=2^4096-1 "EN")**
4. [Proving primality](//primes.utm.edu/prove/ "EN, 2018-01-03")
5. [Mersenne Numbers with no Known Factors](//www.mersenne.org/report_factoring_effort/?exp_lo=2&exp_hi=7650&bits_lo=64&bits_hi=70&exassigned=1 "EN")

# Сообщения приложения Prime95

|Communication thread|Поток сообщений
|:--- |:--- 
|Exchanging program options with server|Обмен параметрами программы с сервером
|Getting assignment from server|Получение задания с сервера
|Sending result to server:|Отправка результата на сервер:
|Updating computer information on the server|Обновление информации о компьютере на сервере

# 