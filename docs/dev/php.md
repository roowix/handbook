# Рекомендации по PHP

## Framework
Фреймворк по умолчанию: Symfony. Это не обязывает вас использовать его везде, но если возник вопрос что использовать то лучше Symfony.

## Тестирование
PHPUnit. Аналогично Symfony необязательно выбирать phpunit, но крайне рекомендуется.

Рекомендуется использовать AAA. Это позволяет стандартизировать тесты и поддерживать их в более-менее одинаковом состоянии 
http://wiki.c2.com/?ArrangeActAssert

## Code style
Если проект не требует иного, то используем PSR
https://www.php-fig.org/psr/psr-12/

Всё, что не описано в PSR стоит описать в проекте в виде dockerfile. 