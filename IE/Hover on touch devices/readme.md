#Некоректное отображение :hover на IE 10 (Touch Device)

[Некоректно работающий пример](https://dinamickadevelopment.github.io/legendary-cases/IE/Hover on touch devices/index_bad.html)

[А это работает отлично](https://dinamickadevelopment.github.io/legendary-cases/IE/Hover on touch devices/index_good.html)

Атрибут реализует роботу  :hover на IE 10 (Touch Device) по привычной логике как в (Chrome, Firefox)

[Решение было найдено здесь!](https://css-tricks.com/forums/topic/ie10-mobiletouch-hover-navigation-problem/#post-151491)

>Microsoft has a solution here. It seems adding aria-haspopup="true" to an element will trigger a hover on first tap, and a click on second tap, when using Win8.
