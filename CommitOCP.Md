Класс Vehicle представляет транспортное средство и содержит приватные поля maxSpeed и type.
Класс также имеет метод calculateAllowedSpeed(), который возвращает максимальную разрешенную скорость.
Применяя принцип открытости-закрытости, класс Vehicle открыт для расширения путем создания подклассов, но закрыт для модификации.

Класс Bus является подклассом Vehicle и представляет автобус. Он переопределяет метод calculateAllowedSpeed(),
чтобы определить максимальную разрешенную скорость для автобуса (равную половине максимальной скорости).
При применении принципа открытости-закрытости класс Bus расширяет функциональность базового класса Vehicle, не изменяя его внутреннюю реализацию.

Класс Car также является подклассом Vehicle и представляет автомобиль.
Он также переопределяет метод calculateAllowedSpeed(),
чтобы определить максимальную разрешенную скорость для автомобиля (равную 80% от максимальной скорости).
При соблюдении принципа открытости-закрытости класс Car расширяет функциональность базового класса Vehicle, не изменяя его внутреннюю реализацию.

Таким образом, принцип открытости-закрытости позволяет расширять функциональность класса Vehicle путем создания подклассов (Bus, Car),
не изменяя код самого класса. Это делает код более гибким и поддерживаемым.