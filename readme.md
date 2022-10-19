Haskell, моё резюме. \

TL;DR \
Изучаю Хаскелль и пытаюсь собрать на нем игровой движок. Собирал эхо-бота для телеграмма. \

В деталях: \

Сложно точно оценить свой уровень, но основной набор тайпклассов мне знаком; Знаю полезные микро-паттерны, вроде фантомных типов, смарт-конструкторов; Хорошо знакомы линзы; Знаком с mtl/монад стаками. С многопоточным программированием не знаком, но общее представление есть. Алгоритмы и структуры данных изучал/изучаю по необходимости. \

Практиковался на небольших проектах для себя и в стол: \
Первая попытка спрограммировать что-то, 2D игра: https://github.com/omegaGreeNya/gloss-juicy-collapse (Демки в readme) \
Тогда я ещё не был знаком с паттернами проектирования и поэтому в какой-то момент остановился, потому что расширять стало слишком сложно. \


По книге Александра Гранина (Functional Design and Architecture) познакомился с принципами проектирования, требованиями к архитектуре приложения, Free-Monad'ами, проектом-полигоном стал очень эксперементальный игровой фреймворк: https://github.com/omegaGreeNya/CakeFree-Sdl2 \

Работал над телеграм-ботом, web топики изучать не сложно. Старался использовать по минимуму зависимостей и абстракций в проекте: https://github.com/omegaGreeNya/chatbot \

Сейчас активно веду разработку следующей итерации игрового фреймворка, основной целью на этот раз выбранна гибкость и расширяемость: https://github.com/omegaGreeNya/chessTactics \
Фреймфорк основан на ECS подходе (библиотека apecs). Он берёт на себя реализацию загрузки, отрисовки, кэша ресурсов, игрового цилка и так далее, всю грязную работу. Пользователю остается только определить скрипты, которые фреймворк будет выполнять. Яркий пример, игровой цикл: https://github.com/omegaGreeNya/chessTactics/blob/main/src/Core/SystemControl/Language.hs \
Шахмат пока нет, есть небольшая демка: https://youtu.be/cTwxNNJ_s34 \

Git:\
Add, commit, push. Большего мне пока не требовалось.\

С английским у меня особых проблем нет, документацию и технические книги могу свободно читать, искать информацию на английском, с письмом похуже, но изъясниться могу.\

email: megamanCake@yandex.ru \
telegram: https://t.me/greencake \
discord: BookCake#1649 \
vk: https://vk.com/egreencake \
