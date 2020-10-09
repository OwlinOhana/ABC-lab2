# ABC-lab2
# Реализовать программу для оценки производительности процессора (benchmark).

С помощью системного таймера (библиотека time.h, функции clock() илиgettimeofday()) или
с помощью процессорного регистра счетчика TSC реализовать оценку в секундах среднего
времени испытания каждой типовой задачи. 

Оценить точность и погрешность (абсолютную и относительную) измерения времени 
(рассчитать дисперсию и среднеквадратическое отклонение). 
                                
                                                      ──────── • ✤ • ────────
                                                           Вывод в файл
                                                      ──────── • ✤ • ────────
                                
✻PModel – Processor Model, модель процессора, на котором проводятся испытания;

✻Task – название выбранной типовой задачи (например, sin, log, saxpy, dgemv, sgemm и др.);

✻OpType – Operand Type, тип операндов используемых при вычислениях типовой задачи;

✻Opt – Optimisations, используемы ключи оптимизации (None, O1, O2 и др.);

✻InsCount – Instruction Count, оценка числа инструкций при выполнении типовой задачи;

✻Timer – название функции обращения к таймеру (для измерения времени);

✻Time – время выполнения отдельного испытания;

✻LNum – Launch Numer, номер испытания типовой задачи.

✻AvTime –Average Time, среднее время выполнения типовой задачи из всех испытаний[секунды];

✻AbsError – Absolute Error, абсолютная погрешность измерения времени в секундах;

✻RelError – Relative Error, относительная погрешность измерения времени в %;

✻TaskPerf – Task Performance, производительность (быстродействие) процессора при выполнении типовой задачи. 
