# Материалы курса "Глубинное обучение", прочитанного на [ФКН ВШЭ](https://cs.hse.ru/) осенью 2020г.

## Преподаватели
Лектор: [Антон Осокин](https://aosokin.github.io/)

Семинаристы: [Ирина Сапарина](https://github.com/saparina), [Максим Рябинин](https://www.hse.ru/staff/mryabinin)

[О курсе](lectures/DL20-fall-about.pdf): программа, схема оценки

## Программа курса
* Введение (лекция 1: [слайды](lectures/DL20-fall-lecture1-intro.pdf), [видео](https://youtu.be/k3QZU5a1oRA))
* Основные концепции
  - Механика нейросетей и backprop
  - Виды архитектур
  - Обучение и регуляризация
  - Best practices
* Продвинутые темы
  - Применения для обработки языка
  - Применения в компьютерном зрении
  - Adversarial X
  - Вероятностные модели
  - Дифференцируемое программирование
  - Недифференцируемые модели
  - Ускорение и внедрение моделей

## Disclaimer
Курс "Глубинное обучение" разрабатывался не как онлайн-курс, а как классический университетский курс с лекциями и семинарами.
Тем не менее, мы решили выложить все материалы в открытый доступ под [лицензией Apache 2.0](../LICENSE) на случай если они кому-то будут полезны.
Единственная просьба, **пожалуйста, не выкладывайте решения семинаров в открытый доступ!** 
  
## Материалы
Все материалы курса на **русском** языке!

Выложены следующие материалы:
* [Презентации лекций](lectures)
* [Jupyter ноутбуки семинаров](seminars) 

**Пожалуйста, не выкладывайте решения семинаров в открытый доступ!** Мы хотим переиспользовать материалы на следующих итерациях курса.
 
## Технические требования семинаров
Все семинары разрабатывались для выполнения на обычных ноутбуках, т.е., не требуют значительных вычислительных ресурсов (в частности не требуют GPU). Тем не менее требования к железу ненулевые, и на некоторых компьютерах все работает очень медленно. Бесплатные вычислительные ресурсы (в том числе с GPU) можно получить, например, на сайте https://colab.research.google.com.

В рамках курса мы использовали python 3.6, pytorch v1.6.0, torchvision v0.7.0. Поддержка других библиотек и других версий python и pytorch не осуществлялась.
 
Для настройки библиотек мы рекомендуем использовать менеджер пакетов [Anaconda](https://www.anaconda.com/) (есть для Linux, OS X, Windows). Для установки в Linux, OS X и Windows смотрите инструкции на сайте http://pytorch.org/. 
 