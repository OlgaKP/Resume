### Задача - "Радиоман"

В рамках проекта по созданию "Умного дома" нам нужно научиться управлять радио.

Цели: создать класс Radio, в котором должны храниться следующие поля:

1. Номер текущей (прослушиваемой) радиостанции
2. Громкость звука
3. Требования к работе с радиостанциями:

**Номер текущей радиостанции изменяется в пределах от 0 до 9:**
* Если текущая радиостанция - 9 и клиент нажал на кнопку next (следующая) на пульте, то текущей должна стать 0-ая; в остальных случаях радио переключается просто на следующую станцию.
* Если текущая радиостанция - 0 и клиент нажал на кнопку prev (предыдущая) на пульте, то текущей должна стать 9-ая; в остальных случаях радиопереключается просто на предыдущую станцию.
* Клиент должен иметь возможность выставлять номер радиостанции через прямое указание её номера.

**Требования к работе с уровнем громкости звука:**
* Клиент должен иметь возможность увеличивать и уменьшать уровень громкости звука (в пределах от 0 до 10)*
* Если уровень громкости звука достиг максимального значения, то дальнейшее нажатие на + не должно ни к чему приводить.
* Если уровень громкости звука достиг минимального значения, то дальнейшее нажатие на - не должно ни к чему приводить.

***В итоге, нужно создать проект, в котором:***
1. Подключить плагин Surefire так, чтобы сборка падала в случае отсутсвия тестов.
2. Подключить плагин JaCoCo в режиме генерации отчётов (обрушать сборку по покрытию не нужно).
3. Реализовать нужные классы и методы.
4. Написать автотесты на методы, содержащие логику, добившись 100% покрытия по branch'ам.
5. Подключить CI на базе Github Actions и выложить всё на Github.

### Результат - ["Радиоман"](https://github.com/OlgaKP/Radioman)

