    # Testing

    * Что такое автоматизированное тестирование, и в чём отличие от ручного тестирования?
    * Что такое unit-test?
    * Что такое TDD?
    * В чем преимущество TDD? Зачем писать сначала тесты, а потом код?
    * Что такое регрессионные баги и как автоматические тесты помогают их решать?
    * Почему сайд-эффекты ухудшают тестируемость кода?
    * Что такое mock и когда их стоит применять?
    * Что такое шпион и когда их стоит применять?
    * Стоит ли тестировать приватные методы класса? Почему?
    * Зачем группировать отдельные тесты внутри unit-тестов?
    * Какое время должен длиться идеальный рабочий цикл: _написание теста -> изменение функциональности -> рефакторинг_?
    * Какие библиотеки есть для создания тестов и их запуска (и чем отличаются друг от друга)?
    * Как тесты помогают со входом в проект новичков?
    * Как тесты помогают в документировании проекта?
    * Как тесты ускоряют получение фидбека от проделанной работы и почему этот фидбек важен?
    * Какие этапы ручного тестирования помогают избегать unit-тесты?
    * Зачем добиваться того, чтобы тесты работали быстро?
    * Как добиваться того, чтобы ошибки в тестах были максимально очевидными?
    * Нужно ли автоматизированно тестировать сами тесты?
    * Что такое граничные условия? Зачем их тестировать?
    * Что такое heisenbug? Какие есть способы их дебаггинга?
    * Что такое fixture?
    * Что такое покрытие кода тестами? Какие есть инструменты для его анализа?
    * Чем юнит-тесты отличаются от интеграционных тестов? Почему интеграционные сложнее писать и поддерживать?
    * Зачем обращать внимание на закономерности при отказе тестов? В чём может помочь анализ того, какая именно комбинация тестов отвалилась?
    * Как тесты помогают в проектировании? Почему тестируемость модуля является отличным индикатором "чистоты кода"?
    * Как тесты помогают при рефакторинге?
    * В чём преимущества правила одной концепции на один unit-тест?
    * В чём преимущества изолированных друг от друга тестов?
    * Как найти баланс между количеством тестов и покрытием кода? Какие проблемы могут быть из-за излишнего количества юнит-тестов?
    * Что такое пирамида тестирования? Какую роль там играют тесты? Какую роль там играет статический анализ кода?
    * Являются ли типы полной заменой unit-тестам? Почему?
    * Что такое end-to-end тесты? В чём отличие от интеграционных?
    * Когда тесты действительно замедляют разработку, а когда ускоряют?
    * Являются ли тесты полноправной частью системы и кодовой базы?
    * Почему тестирование становится менее удобным, если тестировать не только публичные, но и приватные методы?
    * Что такое Test Double и Fake? В чём отличие от Mock и Stub?
    * Какая разница между тестированием с behavior verification и со state verification?
    * Почему применение Mocks провоцирует behavior verification?
    * Что такое Solitary и Sociable тесты? В чём преимущества Solitary тестов? Есть ли преимущества у Sociable тестов?
    * Почему применение Mocks упрощает проектирование методом "outside-in"?
    * Зачем стремиться к тому, чтобы тесты можно было запускать максимально удобно и всего одной командой?
    * Стоит ли писать "учебные" интеграционные тесты, которые запускаются только вручную и только для тестирования внешнего API (например, Web API Github)?


    ### Ресурсы

    * [A quick guide to Manual Testing Vs Automated Testing](https://reqtest.com/testing-blog/manual-testing-vs-automated-testing/)
    * [Зачем нужны юнит-тесты](https://tproger.ru/translations/unit-tests-purposes/)
    * [Как, используя TDD, сократить время разработки](https://www.simbirsoft.com/blog/razrabotka-cherez-testirovanie-polza-i-vred/)
    * [Об использовании модульных тестов и TDD](https://eax.me/unit-testing/)
    * [Автоматические тесты при помощи chai и mocha](https://learn.javascript.ru/testing/)
    * [Знакомство с фронтенд-тестированием. Часть первая. Введение](https://tproger.ru/translations/frontend-testing-1/)
    * [Осторожно! Возможны побочные эффекты](http://blog.csssr.ru/2017/10/07/side-effects)
    * [JS testing tools overview](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2019-264e19514d0a)
    * Чистый код. Создание, анализ, рефакторинг (Роберт Мартин, глава 9 "Модульные тесты")
    * [Гид по ручному тестированию приложений: преимущества, этапы и методологии](https://habr.com/ru/company/skillbox/blog/418889/)
    * [Test first by R. Marting](https://blog.cleancoder.com/uncle-bob/2013/09/23/Test-first.html)
    * [5 Questions Every Unit Test Must Answer by E. Elliott](https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d)
    * [Unit Tests, How to Write Testable Code and Why it Matters](https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters)
    * [UnitTest by M. Fowler](https://martinfowler.com/bliki/UnitTest.html)
    * [Unit Tests from XP](http://www.extremeprogramming.org/rules/unittests.html)
    * [Test Reviews Vs. Code Reviews - Some Helpful Tips](https://osherove.com/blog/2007/3/13/test-reviews-vs-code-reviews-some-helpful-tips.html)
    * [Types and Tests](https://blog.cleancoder.com/uncle-bob/2017/01/13/TypesAndTests.html)
    * [Mocks Aren't Stubs](https://www.martinfowler.com/articles/mocksArentStubs.html)
    * [We don't write tests. There just isn't time for luxuries.](https://www.jamesgolick.com/2007/8/22/we-dont-write-tests-there-just-isnt-time-for-luxuries.html)
    * [Юнит-тестирование для чайников](https://habr.com/en/post/169381/)
