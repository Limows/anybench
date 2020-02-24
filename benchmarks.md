## Список бенчмарков

* Dhrystone
* Whetstone 
* LINPACK
* MP MFLOPS
* Memspeed
* LLoops
* Coremark
* Scimark 2

### Dhrystone

> Dhrystone - синтетический бенчмарк, который был написан Reinhold P. Weicker в 1984 году.
> Данный бенчмарк не использует операции с плавающей запятой, а версия 2.1 написана так, чтобы исключить возможность сильных оптимизаций при компиляции.
> Бенчмарк выдаёт результаты в VAX Dhrystones в секунду, где 1 VAX DMIPS = Dhrystones в секунду делить на 1757.

### Whetstone

> Whetstone - синтетический бенчмарк, который был написан Harold Curnow в 1972 году на языке Fortran.
> Позже был переписан на языке C Roy Longbottom. Данныей бенчмарк выдаёт результаты в MWIPS,
> также промежуточные результаты в MOPS (Миллионов операций в секунду) и MFLOPS (Миллионы вещественных операций с плавующей запятой в секунду).
> Данный бенчмарк производит различне подсчёты: производительность целочисленных и операций с плавующей запятой,
> производительность операций с массивами, с условным оператором, производительность тригонометрических функций и функций возвдения в степень, логарифмов и извлечения корня.

Также мной был написан бенчмарк Whetstone на языках JS (Для тестирования браузера и NodeJS) и C# (Для тестирования Mono, .Net Framework и Dotnet Core), а также я нашёл реализацию на Java.

> Whetstone MP - многопоточный вариант Whetstone.

### LINPACK

> LINPACK бенчмарк, который был написан Jack Dongarra на языке Fortran в 70х годах, позже переписан на язык C.
> Данный бенчмарк считает ситемы линейных уравнений, делает различные операции над двумерными (матрицами) и одномерными (векторами).
> Используется реализация Linpack 100x100 с числами типа float. Реализация бенчмарка хорошо используется для оценки производительности
> различных суперкомпьютеров.

### MP MFLOPS

### Memspeed

### LLoops

### Coremark

### Scimark 2

## Участники

Машины на процессорах x86 (i386) х86-64 (amd64):

* Core i7-2600
* AMD A6-3650
* Atom Z8350
* Core 2 Duo T9400

Машины на процессорах armv6 (armel), armv7 (armhf), armv8 (aarch64):

* Odroid N2 (Amlogic S922X)
* Odroid X2 (Samsung Exynos 4412)
* Orange Pi PC2 (Allwinner H5)
* Orange Pi Win (Allwinner A64)
* Raspberry PI 3 (Broadcom BCM2837B0)
* Raspberry PI (Broadcom BCM2835)
* AWS Graviton (Alpine AL73400)

Машины на процессорах e2k (Elbrus 2000) [v3, v4, v5]:

* E8C-SWTX (Elbrus 8C)
* E8C-E8C4 (Elbrus 8C x4)
* E8C2 (Elbrus 8C2)
* E2S-EL2S4 (Elbrus 4C x4)
* E2S-PC401 (Elbrus 4C)
* MBE1C-PC (Elbrus 1C+)

Машины на процессорах  mips :

* Baikal T1 BFK 

### Таблица со всеми участниками

| Платформа        | Модель процессора                               | Всего ядер (потоков) | Частота  | Архитектура |
| ---------------- | ----------------------------------------------- | -------------------- | -------- | ----------- |
| Core i7-2600     | Intel(R) Core(TM) i7-2600 CPU @ 3.40GHz         | 8                    | 3,400.00 | amd64       |
| Core 2 Duo T9400 | Intel(R) Core(TM) 2 Duo CPU    T9400  @ 2.53GHz | 2                    | 2,530.00 | amd64       |
| AMD A6-3650      | AMD A6-3650 APU with Radeon(tm) HD Graphics     | 4                    | 2,600.00 | amd64       |
| Atom Z8350       | Intel(R) Atom(TM) x5-Z8350 CPU @ 1.44GHz        | 4                    | 1,440.00 | amd64       |
| Raspberry PI     | Broadcom BCM2835                                | 1                    | 700.00   | amd64       |
| AWS Graviton     | Alpine AL73400                                  | 16                   | 2,300.00 | arm         |
| Odroid N2        | Amlogic S922X                                   | 6                    | 1,800.00 | arm         |
| Odroid X2        | Samsung Exynos 4412 (armv7l)                    | 4                    | 1,700.00 | arm         |
| Orange Pi PC2    | Allwinner H5 (aarch64)                          | 4                    | 1,152.00 | arm         |
| Raspberry PI 3   | Broadcom BCM2837B0 (armv8)                      | 4                    | 1,200.00 | arm         |
| Orange Pi Win    | Allwinner A64 (aarch64)                         | 4                    | 1,344.00 | arm         |
| E8C-SWTX         | Elbrus 8C (E8C-SWTX)                            | 8                    | 1,300.00 | e2k         |
| E8C-E8C4         | Elbrus 8C (4 CPU)                               | 32                   | 1,300.00 | e2k         |
| E8C2             | Elbrus 8C2 (E8C2)                               | 8                    | 1,500.00 | e2k         |
| E2S-EL2S4        | Elbrus 4C [EL2S4] (4 CPU)                       | 16                   | 750.00   | e2k         |
| E2S-PC401        | Elbrus 4C [E2S] (pc401)                         | 4                    | 800.00   | e2k         |
| MBE1C-PC         | Elbrus 1C+ (MBE1C-PC)                           | 1                    | 985.00   | e2k         |
| Pentium 4        | Intel(R) Pentium(TM) 4 CPU                      | 1                    | 3,066.00 | i386        |
| Pentium III      | Intel(R) Pentium(TM) III CPU                    | 1                    | 1,000.00 | i386        |
| Baikal T1 BFK    | Baikal-T1 (MIPS P5600 V3.0)                     | 2                    | 1,200.00 | mips        |