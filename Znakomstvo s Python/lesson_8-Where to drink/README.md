## Урок 8. Ищем где выпить

В данном уроке рассматриваются библиотеки geopy, folium - для отображения геометок ближайших баров Москвы на карте, а также работа с Yandex geocoder API.
Скрипт принимает адрес вашего месторасположения и формирует 5 ближайших меток с названиями баров.

![](https://dvmn.org/filer/canonical/1567161408/258/)

### Требования к окружению
python 3.7

### Установка

Требуется установка дополнительных библиотек, файл requirements.txt с зафиксированными версиями пакетов.
* Для установки необходимых библиотек в терминале следует прописать `pip install -r requirements.txt`.

### Запуск скрипта

Для запуска скрипта, необходимо получить [API KEY в кабинете разработчика Яндекс](https://developer.tech.yandex.ru/services/) - добавить файл __.env__ c текстом `MY_API_KEY='ВАШ КЛЮЧ'`. Далее используйте IDE, либо в терминале в папке с программой необходимо прописать `python main.py`.