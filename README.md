# Проект: Путешествие по России


Навыки адаптивной вёрстки сайта, по макету с редактора Figma.

**В Проекте использовал**:
- Построение сеток по Grid;
- Flex - контейнеры
- Медиазапросы по ширине окна браузера. Все точки перелома макета подбирались для каждого блока индивидуально, добиваясь большей плавности в переходе, но в соответствии с контрольными макетами по разрешениям 320рх 768рх 1024рх 1280рх. Выше макет уже не масштабируется.
- Единицы em и rem для текста не использовал, шрифты Inter в значениях (400, 700, 900) подключены локально в двух форматах woff2 и woff. Применено сглаживание шрифтов в корневом стиле page.
- В секциях Lead и Cover и для размера блока и шрифтов применил динамически высчитываемые размеры на основе размера ViewpointWidth (vw). Формула взята из статьи https://vc.ru/dev/178033-dinamicheskoe-masshtabirovanie-elementov-v-css

ссылка на проект: https://aotopkov.github.io/russian-travel/