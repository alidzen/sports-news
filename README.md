# sports-news

Привет! 

Постарался использовать BEM методолгию, а именно АНБ смотрите, что из этого вышло.

Буду признателен за конструктивную обратную связь.

Небольшой style guide в помощь: 

		<!-- Общие положения -->
Длина строки в редакторе: 80 символов максимум.

Использование префиксов для блоков: 

	b- блок (Для явного выделения блоков, элементу ограничивающему блок задаётся 
класс с префиксом (b-, h-, l- об этом ниже) и все стили этого блока описываются 
начиная от этого класса.)

	h- holster (Если нам надо задать отступы у группы блоков или разные отступы 
у одного и того же блока на разных страницах, то удобнее всего использовать для этого 
элемент-обёртку.)

	js- название для JavaScript-классов
	 
	l- layout, служит для расположения блоков (Если блок используется только для 
расположения других блоков, называем его лайаутным блоком, используем для него 
префикс l- и делаем его полностью независимым. Это позволяет сразу видеть в коде 
блоки для расположения и, в случае необходимости, заменить раскладку флоатами на 
таблицу или наоборот.)
		
		<!-- Именование классов. -->
t-template-name 

t-template-name--modifier-name

t-template-name__subcomponent-name--subcomponent-modifier-name

Пример:

t-icon

t-icon--large

t-btn

t-btn--large

t-media

t-media__img

t-media__img--large

t-media__opt

t-media__body

