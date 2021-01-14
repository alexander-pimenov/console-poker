## Консольное приложение, «Рука» в игре в покер.

* Значения карт приведены в виде списка:

ЗНАЧЕНИЯ = ['2', '3', '4', '5', '6', '7', '8', '9', 'T', 'J', 'Q', 'K' , 'A']

>Где T = 10, J = «Валет», Q = «Дама», K = «Король» и A - «Туз»

* Возможные «масти»

МАСТИ = ['C', 'D', 'H', 'S']

>Где C = Clubs (Крести), D = Diamonds(Бубны), ​​H = Hearts(Черви) и S = Spades (Пики).

Рука содержит 5 карт и неизменна, например:

('4D 4C 4H 7H 8D')

('4D 3D 3D 7H AD')

Возможные «ценности», в соответствии с правилами покера, задаются как (по порядку, от низкого до высокого значения):

VALUES = [HIGH_CARD, ONE_PAIR, TWO_PAIR, THREE_OF_A_KIND, STRAIGHT,

FLUSH, FULL_HOUSE, FOUR_OF_A_KIND, STRAIGHT_FLUSH, ROYAL_FLUSH]

### Пример:

_<hand [TS, JS, QS, KS, AS], 'Royal Flush'>_

_<hand [5S, 6S, 7S, 8S, 9S], 'Straight Flush'>_

_<hand [7S, TC, TH, TS, TD], 'Four of a Kind'>_

_<hand [5H, 5C, QD, QC, QS], 'Full House'>_

_<hand [2D, 3D, 7D, QD, AD], 'Flush'>_

_<hand [4D, 5D, 6D, 7H, 8D], 'Straight'>_
