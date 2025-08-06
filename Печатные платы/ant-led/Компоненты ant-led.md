---
автор: Арсений Игоревич Лохматов
дата: 31 июля 2025
---

| Описание                | Кол-во (x1) | Кол-во (x30) | Ссылка                                                                                                                                                                                                                                                                              |
| ----------------------- | ----------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Светодиод зелёный       | 10          | 300          | [GNL-0805PGC-TL](https://www.chipdip.ru/product/gnl-0805pgc-tl)                                                                                                                                                                                                                     |
| Светодиод красный       | 1           | 30           | [GNL-0805PGC-TL](https://www.chipdip.ru/product/gnl-0805src)                                                                                                                                                                                                                        |
| Компаратор              | 1           | 30           | [LM393DR](https://www.chipdip.ru/product/lm393d-ti?utm_source=direct&utm_medium=cpc&utm_campaign=Y_dinamicheskaya&utm_content=text1_ya&utm_term=---autotargeting&position_type=premium&yclid=15985112502279340031)                                                                  |
| Фоторезистор            | 1           | 30           | [GL5516](https://www.chipdip.ru/product/gl5516)                                                                                                                                                                                                                                     |
| Кнопка тактовая         | 4           | 120          | [KLS7-TS6604](https://www.chipdip.ru/product/kls7-ts6604-7.0-180-b-it-1102sb?utm_source=direct&utm_medium=cpc&utm_campaign=Y_dinamicheskaya&utm_content=text1_ya&utm_term=---autotargeting&position_type=premium&yclid=3416740984969494527) нужно заменить от фирмы TE Connectivity |
| Транзистор              | 8           | 240          | [DMG2302U-7](https://www.chipdip.ru/product0/8017538181)                                                                                                                                                                                                                            |
| Резистор 0805 47 Om     | 8           | 240          |                                                                                                                                                                                                                                                                                     |
| Резистор 0805 10 kOm    | 5           | 150          |                                                                                                                                                                                                                                                                                     |
| Резистор 0805 100 kOm   | 8           | 240          |                                                                                                                                                                                                                                                                                     |
| Резистор 1206 47 Om     | 2           | 60           |                                                                                                                                                                                                                                                                                     |
| Резистор 1206 220 Om    | 1           | 30           |                                                                                                                                                                                                                                                                                     |
| Резистор 1206 10 kOm    | 2           | 60           |                                                                                                                                                                                                                                                                                     |
| Конденсатор 0805 100 nf | 4           | 120          |                                                                                                                                                                                                                                                                                     |
| Тест поинт крючок       | 1           | 30           | [Test Plugs 5003](https://www.chipdip.ru/product0/8008363707)                                                                                                                                                                                                                       |
| Пин штыревой            | 2           | 60           | [DG333J](https://www.chipdip.ru/product0/8031859908)                                                                                                                                                                                                                                |

Параметр RC фильтра для фильтрации дребезга тактовых кнопок: 
- R = 10 kOm
- C = 100 nf
- $\tau$ = $R\cdot C$ = 10 ns
Расчёт номинал резистора для зелёных светодиодов:
- $V_{CC}$ = 3.3 V
- $V_{LED}$ = 2.5 V
- $I_{LED}$ = 20 mA
- R = $\frac{V_{CC}-V_{LED}}{I_{LED}}$ = $\frac{3.3-2.5}{0.02}$ = 40 Om
- **R = 47 Om**
Номинал резистора для красных светодиодов:
- $V_{CC}$ = 5 V
- $V_{LED}$ = 2 V
- $I_{LED}$ = 20 mA
- R = $\frac{V_{CC}-V_{LED}}{I_{LED}}$ = $\frac{5-2}{0.02}$ = 150 Om
- **R = 220 Om** #запас
