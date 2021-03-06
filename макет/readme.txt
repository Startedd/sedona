
Это макет с более сложной сеткой. Верстать его можно двумя способами:

1. Как остальные макеты интенсива - под ширину фиксированную ширину 1280px, с центровкой основного контента и с некоторыми блоками, которые тянутся на всю ширину. В этом случае пользуйтесь макетами с суффиксом "-1280"

2. С дополнительной резиновостью, когда макет тянется с минимальной ширины 768 px. Это более сложный способ, который вы можете попробовать, если уверены в своих силах. Чтобы сетка вела себя правильно, вам поможет описание от дизайнера ниже, а также дополнительные макеты с суффиксом "-768", в которых видно поведение макета на минимальной ширине.

Описание сетки от дизайнера:

Итак, сетка не стандартная. Минимальная ширина: 768 px. Основа ее — три колонки равной ширины (33%), стоящие вплотную друг к другу без отступов. Теперь пойдем по главной странице сверху вниз:
— Главное меню. Главное меню это пять ячеек по 20% ширины. В каждой из них контент лежит по центру. Это 4 пункта меню и логотип.
— Крупное фото. Фотография занимает 100% ширины. В ее нижней части есть белая маска, она также масштабируется на 100% ширины, но в отличие от фотографии меняет свои пропорции (то есть высота остается постоянной, а ширина — 100%)
— Текстовые блоки лежат поверх большого фото в своих фиксированных размерах и центруются.
— Далее видим вступительный текст, с ним все просто, он центруется, размер не меняет.
— Затем начинается деление контентной зоны на три равные столбца и дальнейший контент вписывается в них.
— Фотографии, занимающие по две трети ширины вставляются так, чтобы обрезаться сверху и снизу при увеличении размера (ширина 66%, высота подстраивается под ширину, чтобы не нарушать пропорций, но фото не выходит за отведенную для него зону)
— Все тексты имеют фиксированные размеры и межстрочные интервалы, не меняются в зависимости от ширины вьюпорта
— Следом за контентной зоной идет блок поиска гостиницы. Он фиксированный по всем направлениям.
— Карта, лежащая на фоне может быть как гугл-картой с выключенными контролами, так и просто картинкой. В макете есть картинка шириной 2560 px, этого должно хватить, тем более, что нам понадобится максимум 1200 px, мы узнаем позже, почему. Таким образом карта не масштабируется, а просто является фоном, который частично показывается в имеющемся окне.
— Футер также состоит из трех колонок. В рамках каждой из них содержимое центруется.

Страница выбора гостиниц:

— Главное меню и футер совпадают с главной страницей
— Фоновое фото другое (размытое и меньшего размера), но также масштабируется на 100% ширины
— Элементы фильтра поиска и другие элементы данной страницы ("найдено:3", фото гостиниц) имеют отступ от левого края, который высчитывается так: ширина вьюпорта делится на 5, затем из оставшегося вычитается 93 px, полученное значение делим на два и получаем величину отступа от левого края. Фактически — это отступ перед пунктом меню "информация". Аналогичное значение принимаем и за правый отступ.

При достижении 1200 px сетка перестает масштабироваться дальше, и слева и справа от нее появляется серый фон, на который сайт бросает легкую тень. Таким образом мы защищаемся от чрезмерного вытягивания всех блоков по горизонтали.