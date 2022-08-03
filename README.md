# iOS RxTraining

**Упражнения для практики реактивного программирования**

В данном практикуме содержится несколько блоков для тренировки применения реактивных операторов:
*  RxCreating - создание последовательностей
*  RxCombining - комбинирование последовательностей
*  RxFiltering - фильтрация элементов
*  RxTranforming - преобразование элементов
*  RxError - обработка событий ошибки
*  RxTraits - создание и использование Traits
*  RxAdvanced - усложеннные задания на применение комбинаций операторов из различных блоков

**Как работать с заданиями?**

В каждом блоке заданий представлены несколько методов с описанием и реализацией по умолчания (обычно это эмит ошибки NotImplemented). Для каждого задания необходимо написать соответствующую описанию реализацию, которая проходит юнит тесты для этого метода. Названия тестов имеют следующую структуру test<тестируемый метод><(необязательно) кейс, который тестируется>. После реализации всех методов все тесты для данного блока должны успешно проходить.

**Источники для изучения:**
*  [RxMarbles: визуальное представление операторов](https://rxmarbles.com)
*  [RxSwift: документация](https://github.com/ReactiveX/RxSwift)
*  [Шпаргалка по операторам](https://habr.com/ru/post/281292/) (ВНИМАНИЕ: в статье неверное описание и примеры для оператора throttle. Оператор верно представлен в RxMarbles)