Реализована загрузка файлов. Пользователь может загрузить файл (размером не более 50 мегабайт) и задать ему новое имя, с которым файл сохранится на сервере. Если пользователь не укажет новое имя, то файл загрузится со старым именем.
При успешной загрузке пользователь будет перенаправлен на страницу с сообщением "Файл успешно загружен", при неудачной загрузке пользователь будет перенаправлен на страницу с сообщением "Файл не был загружен".
Структура: главная страница(index.php), таблица стилей (main.css), папка uploads(для загружаемых файлов), страница с ошибкой(error_upload.php), страница с сообщением об успехе (succes_upload.php).