# compute_lab6

Латиков Александр, вариант 5, задача 8.11.5
Задача - необходимо решить систему уравнений:

x' = -sig(x - y)

y' = -xz + rx - y

z' = xy - bz

Начальные условия: x(0) = y(0) = z(0) = 1

b = 8 / 3, sig = 10, r = 28, 0 <= t <= 50

Для решения задачи используются методы Рунге-Кутты 1-4 порядков

Результаты решения диффура с шагом h = 0.001 для 1-4 порядка апроксимации выложены в 1-4.txt. Для краткости выведен только каждый 100-ый отсчет.
Визуализация решения представлена в 1-4.png, если надо посмотреть с разных сторон, то можно покрутить модель в .ipynb

Устойчивых положений равновесия у уравнения нет, для разных методов можно наблюдать значительное расхождение на дистанции t = 50.
Отсутствие положений равновесия и хаотичность решения подтверждается здесь: https://en.wikipedia.org/wiki/Lorenz_system .
