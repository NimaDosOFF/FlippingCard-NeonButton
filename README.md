# FlippingCard-NeonButton
https://nimadosoff.github.io/FlippingCard-NeonButton/
# Создание анимаций карточки и кнопки с помошью html и css
<p align='center'>
  
![ezgif-4-0fbcf6ba5c](https://github.com/NimaDosOFF/FlippingCard-NeonButton/assets/133951460/41732bbc-50a2-4e82-98ca-ca5f939badc1)

  

## Языки программирования
- **HTML5**
  
- **CSS3**

## Актуальность

  
На сайте анимации могут решать целый ряд конкретных задач. Одна из них – заполнение времени, которое пользователю нужно ждать загрузки страницы. Смотреть на статичную страницу не так интересно, как на красивую анимацию. В итоге те пользователи, которые могли бы покинуть сайт, остаются на нем – и как результат растет конверсия.

Также анимации могут быть использованы для приветствий и создания нужного настроения – для этого, например, подходят фоновые видео. Помимо этого, анимации отлично подходят для сторителлинга – с их помощью можно быстро рассказать историю или показать работу продукта без большого количества картинок и текста.
  
  
Еще одная важная задача анимаций – они делают сайт более удобным для пользователя, оптимизируют взаимодействия с веб-страницей. Например, карусель с изображениями куда удобнее, чем длинный список картинок с подписями. В свою очередь, анимированные боковые меню могут давать возможность сразу получить больше информации, например, о товаре, без необходимости скроллить.
  
  
Еще одная важная задача анимаций – они делают сайт более удобным для пользователя, оптимизируют взаимодействия с веб-страницей. Например, карусель с изображениями куда удобнее, чем длинный список картинок с подписями. В свою очередь, анимированные боковые меню могут давать возможность сразу получить больше информации, например, о товаре, без необходимости скроллить.
## Ход работы
  
  Всего в проекте у меня находится три файла (хотя можно было обойтись и двумя), не считая картинки: Основной **Index.html** и два файла **css** для карточки и кнопки раздельно.
  
  - В файле index.html опишем наши объекты, присвоим им классы для дальнейшей работы с ними в **.css** файлах
  
  ![image](https://github.com/NimaDosOFF/FlippingCard-NeonButton/assets/133951460/a94ac06a-e69a-4209-8532-22bc94f0a7ed)

  - Привяжем наши файлы
  
  ![image](https://github.com/NimaDosOFF/FlippingCard-NeonButton/assets/133951460/9f978307-bce6-4a81-8182-2c61655d5e2e)

  
  - Основная работа у нас будет в файлах **css**. Уже можно переходить к ним
  
  ## Карточка
  
  Основные составляющие данной анимации будут свойства:
- `position: relative` и `position: absolute` для того, чтобы одна сторона кароточки перекрывалась другой и текст на задней стороне был отзеркален, чтобы при повороте текст на задней строне был читаем. 
- Также для самого поворота использовал свойство `transform:rotateY(180deg)`, которое позволяет перевернуть карточку на 180 градусов по оси Y. 
- Для того, чтобы поворот осуществлялся при наведении я использовал псевдокласс `hover`. 
- C помощью свойства `perspective` мы задаём глубину нашей карточке, чтобы поворот выглядел объёмно.
  
  ## Кнопка
  
  - Очень важным является созданиее в HTML файле отдельных классов для каждого движущегося элемента по краям текста.
  
  # Ключевые составляющие данной анимации:
  
  - Использование в блоке `.button` свойство `overflow: hidden` для того чтобы все объекты уходящие за пределы кнопки исчезали
  
  - Использование псевдо класса `hover` для анимации каждого элемента при наведении мыши, а также для того, чтобы кнопка загорелась
  - Использование `box-shadow` для формирования тени вокруг кнопки, которая впоследствии будет выглядеть как свечение этоф же кнопки
  
## Ссылки на обучающий материал
  
 https://www.youtube.com/watch?v=Kdal-3AfeRc
  
  https://www.youtube.com/watch?v=__rxApMI_Us&list=PL3LQJkGQtzc56HquxrkwPdQt9Q1wHm21P&index=17

## Посетить сайт
  
https://nimadosoff.github.io/FlippingCard-NeonButton/

## Контакты
- VK : [Дмитрий Носов](https://vk.com/nimadosov)
- [Telegram](https://t.me/dosoff)
- mail : noa3eng@yandex.ru

