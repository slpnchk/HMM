# HMM...

Неформальная постановка задачи
----
Разработать проект дуэли двух игроков наподобие heroes of might and magic. 

**Особенности**
>- Поле боя должно представлять из себя координатную сетку
>- В бою должны принимать участие 2 игрока.
>- Каждому игроку могут принадлежать некоторое кол-во войнов, боевых машин, а также сооружений для защиты
>- Все войны, боевые машины и сооружения должны обладать некоторым колличесвом очков здоровья, а также силой урона.
>- Все войны должны уметь ходить по полю боя на определенное кол-во клеток поля.
>- Боевые машины представлены: Палаткой скророй помощи(может лечить войнов), Баллистой(наносит урон на расстоянии), Катапультой(наносит урон крепости противника).
>- Победедой игрока I считается полная потеря войнов игроком II. 


**14.04. Текущие задачи:**
>- OK - Сделать что-то с атакой у creature, чтобы по умолчанию существо не могло атаковать(возвращало false). бить мог только какой-нибудь класс воин(возвращало true). сейчас так реализовано у лучника и доктора
>- OK - Организовать проверку корректности ввода координат во время хода игроков.
>- OK - Научиться спрашивать перед ходом у игрока не желает ли он пропустить ход.
>- OK - Добавить рандобный класс монах(:public creature, public doctor)
>- OK - Написать рандобный класс эльф(:public creature, public archer)
>- Добавиьт специальный include для main

**28.04. задачи на графику**
>- OK - нарисовать текстуры персонажей. персонажи игрока 1 -красные(смотрят на право). игрока 2-синие(смотрят на лево).
>- OK - перенести .printmap в класс the_game. Чтобы у него был доступ к параметрам creature
>- OK - персонажа, чей ход, рисовать на другом фоне

**18.05. задачи на графику**
>- OK - закрашивание доступных для хода клеток
>- OK - печать урона от всех возможных ударов.
>- OK - задать интервалы силы атаки и рандомизировать силу удара.
>- OK - графический вывод логов предыдущего удара

**20.05. задачи**
>- на данный момент выигрывает тот, у кого в начале было больше существ. Исправить
