# MAI-2_sem-practica

*Для работы программ необходим браузер Chrome, а также файл "chromedriver", который находится в репозитории*

В своей работе я использовал фреймворк Selenium. Он предназначен для тестирования, но я использовал его для скачивания картинок и записей с камеры наблюдения из интернета. 

# download_file_from_inthernet.py

Данный скрипт может подключиться к указанной ссылке и скачивать видео с камеры наблюдения. Также он может скачать картинку по указанной ссылке.

# download_from_google.py

Данный скрипт скачаивает необходимое количество картинок с сайта Google по указанной теме. На вход указывается запрос; количество фотографий, которые надо скачать; минимальное разрешение (в пикселях). 

# download_from_yandex.py

Данный скрипт скачаивает необходимое количество картинок с сайта Yandex по указанной теме. На вход указывается запрос; количество фотографий, которые надо скачать; минимальное разрешение (в пикселях). 

# get_webcam.py

Данный скрипт Подкличается к разным сайтам, парсит их.
Может вывести все категории видео (вывод ссылок опционален), которые указаны на обработанных сайтах. 
Можем дать ссылку (которую получили от программы способом, который описан строской выше) и начать скачивать запись с камеры.