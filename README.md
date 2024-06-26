Создание видео с бегущей строкой в формате mp4.
Используется Python 3.12.3. Установить зависимости:
```shell
pip install -r requirements.txt
```
При запуске можно передать следующие параметры:
```
--text Текст бегущей строки (default='Hello, world!')
--outdir Каталог для сохранения видео (default='.')
--name Имя видеофайла (default='runstring')
--fps Число кадров в секунду (default=24)
```
Например, запуск 
```
python runstring.py --text="скрипт работает!" --fps=30 --name="my video"
```
создаст в текущем каталоге файл `my video.mp4`.