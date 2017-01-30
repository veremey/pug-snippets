Для правильной работы сниппетов для [PUG](https://pugjs.org/api/getting-started.html) нужно проделать следующие манипуляции:

`C:\Users\%UserName%\AppData\Roaming\Sublime Text 3\Packages\User\`

и в это место клонировать репозиторий.
Перезагрузить SublimeText3 и смело использовать сниппеты в своих целях.


## Сниппеты

### Jade

#### Case

case =>
```pug
case variable
    when condition
        //- code
    default
        //- code
```

#### Условия

if =>
```pug
if condition
    //- code
```

ife =>
```pug
if condition
    //- code
else
    //- code
```

unl =>
```pug
unless condition
    //- code
```

#### Doctype

doc =>
```pug
doctype html
```


#### Фильтры

cof =>
```pug
:coffeescript
    # code
```

less =>
```pug
:less
    // code
```

md =>
```pug
:markdown
    <!-- code -->
```

styl =>
```pug
:stylus
    // code
```

#### Вставки

inc =>
```pug
include file.pug
```

#### Наследование

ext =>
```pug
extends file.pug
```

blk =>
```pug
block name
```

app =>
```pug
append name
```

pre =>
```pug
prepend name
```
 [docs](https://pugjs.org/language/inheritance.html#block-append-prepend)

#### Итерации

each =>
```pug
each value in variable
    //- code
```

while =>
```pug
while condition
    //- code
```

#### Миксины

mix =>
```pug
mixin name(param)
    //- code
```

#### Теги

a =>
```pug
a(href='№') text
```

btn =>
```pug
button(type='submit') name
```

form =>
```pug
form(method='', action='', autocomplete='on')
```

img =>
```pug
img(src='/static/img/}', alt='изображение')
```

inp =>
```pug
input(type='text', autocomplete='on')
```

link =>
```pug
link(rel='stylesheet',  href='static/css/app.css')
```

script =>
```pug
script(src='static/js/app.js')
```

#### Атрибуты

aria =>
```pug
aria-=''
```

ariah =>
```pug
aria-hidden=true
```

class =>
```pug
class=''
```

data =>
```pug
data-=''
```

