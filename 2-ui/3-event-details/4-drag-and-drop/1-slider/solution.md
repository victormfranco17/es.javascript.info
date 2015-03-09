
Как можно видеть из HTML/CSS, слайдер -- это `DIV`, подкрашенный фоном/градиентом, внутри которого находится другой `DIV`, оформленный как бегунок, с `position:relative`.

Бегунок немного поднят, и вылезает по высоте из родителя.

На этой основе мы реализуем горизонтальный Drag'n'Drop, ограниченный по ширине. Его особенность -- в `position:relative` у переносимого элемента, т.е. координата ставится не абсолютная, а относительно родителя.