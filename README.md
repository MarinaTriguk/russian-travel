# Проект: Путешествие по России

### Обзор
Проект называется "Путешествие по России".

Проект сделан по макету из фигмы и основан на технологии адаптивной верстки. 

### Плавное изменение размеров и отступов
Для плавного изменения размеров, отступов при изменении размера окна или масштаба добавила в css немного математики.
Например, в макете шириной 320px отступ у элемента составляет 32px, а в макете шириной 768px - 54px. Можно записать
такой отступ в виде calc(a vw + b px). a и b можно найти из формул

a = (54 - 32) / (768 - 320), b = (32 * 768 - 54 * 320) / (768 - 320).

В нашем примере получается a = 0,049, b = 16, значит в css пишем

calc(4.9vw + 16px)

При изменении размеров окна отступ будет плавно меняться от 32px до 54px, точки перелома не будут сильно заметны.

Формулу можно записать в электронную таблицу и получать новые calc очень быстро.

### Планы на будущее
Планирую в будущем сделать проект, посвященный собственным впечатлениям от местах, которые я посетила. 
 




