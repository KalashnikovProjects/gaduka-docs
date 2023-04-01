Особенности языка
=================

Особые названия
~~~~~~~~~~~~~~~

В гадюке есть названия, которые по техническим причинам нельзя использовать в проекте.

Переменные не могут иметь данные названия:

'eval', "exec", "PIL", "os", "sys", "Image", 'exit', "import", "lambda",
                     "ImageDraw", "ImageFont", 'compiler_data', 'ImageFilter', "del",
                     "return", "assert", "nonlocal", "global", "super", 'quit', 'raise'

=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======
