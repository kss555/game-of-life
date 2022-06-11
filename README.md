# Game of life

## Как запустить игру?
1. Клонируем репозиторий или скачиваем его как zip-архив
2. Двойным кликом открываем файл `game-of-life.html` в браузере Chrome (в других браузерах не тестировал)

## Правила

- Место действия игры — размеченная на клетки плоскость, которая может быть безграничной, ограниченной, или замкнутой.
- Каждая клетка на этой поверхности имеет восемь соседей, окружающих её, и может находиться в двух состояниях: быть «живой» (заполненной) или «мёртвой» (пустой).
- Распределение живых клеток в начале игры называется первым поколением. Каждое следующее поколение рассчитывается на основе предыдущего по таким правилам:
  - в пустой (мёртвой) клетке, с которой соседствуют три живые клетки, зарождается жизнь;
  - если у живой клетки есть две или три живые соседки, то эта клетка продолжает жить; в противном случае (если живых соседей меньше двух или больше трёх) клетка умирает («от одиночества» или «от перенаселённости»).
- Игра прекращается, если
  - на поле не останется ни одной «живой» клетки;
  - конфигурация на очередном шаге в точности (без сдвигов и поворотов) повторит себя же на одном из более ранних шагов (складывается периодическая конфигурация)
  - при очередном шаге ни одна из клеток не меняет своего состояния (предыдущее правило действует на один шаг назад, складывается стабильная конфигурация)

Игрок не принимает активного участия в игре. Он лишь расставляет или генерирует начальную конфигурацию «живых» клеток, которые затем изменяются согласно правилам. Несмотря на простоту правил, в игре может возникать огромное разнообразие форм.

Источник: https://ru.wikipedia.org/wiki/%D0%98%D0%B3%D1%80%D0%B0_%C2%AB%D0%96%D0%B8%D0%B7%D0%BD%D1%8C%C2%BB
