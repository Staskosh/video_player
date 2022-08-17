## Создаем видео плеер.

Данный скрипт позволит воспроизводить видео онлайн.

## Demo
Для использования сайта онлайн воспользуйтесь [репозиторием](https://github.com/Staskosh/video-player/)

Пример [демо](https://staskosh.github.io/video_player/)

## Как установить

Скачай программу себе на компьютер.

Создай [виртуальное окружение](https://python-scripts.com/virtualenv) для проекта.
Установи зависимости.
```bash
pip install -r requirements.txt
```
Ввести адрес видео в файле index.html.
```html
<script type="text/javascript">
    createPlayer({
      elementId: 'player',
      src: 'Тут ссылка на видео',
    });
  </script>
```
Запусти скрипт.
```bash
python render_page.py
```

