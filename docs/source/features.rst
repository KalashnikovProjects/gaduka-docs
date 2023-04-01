Особенности языка
=================

Особые названия
~~~~~~~~~~~~~~~

В гадюке есть названия, которые по техническим причинам нельзя использовать в проекте.

Переменные не могут иметь данные названия:

'eval', "exec", "PIL", "os", "sys", "Image", 'exit', "import", "lambda",
                     "ImageDraw", "ImageFont", 'compiler_data', 'ImageFilter', "del",
                     "return", "assert", "nonlocal", "global", "super", 'quit', 'raise'

=====  =====  ======  ===========  =============  ======  ======
eval   PIL    exit    ImageFont    compiler_data  lambda  quit
exec   Image  sys     ImageFilter  nonlocal       global  super
os     True   import  ImageDraw    assert         return  assert 
=====  =====  ======  ===========  =============  ======  ======
