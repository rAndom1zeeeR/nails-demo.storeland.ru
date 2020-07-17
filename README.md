<h1>StoreLand Template NodeJS Editor</h1>
<p>:computer: Сборщик для разработки шаблонов Storeland на локальном диске</p>

#### Порядок работы

* Устанавливаем <a target="_blank" href="//nodejs.org/en/"><strong>Node.js</strong></a> на компьютер (LTS версию)
* Устанавливаем глобально <b>Gulp</b> `npm install -g gulp-cli gulp`
* Устанавливаем зависимости командой `npm install`
* Заполняем настройки в файле `storeland-uploader-config.json`
* Скачиваем файлы шаблона командой: `gulp download`
* Запускаем сборку командой: `gulp`

#### Файл настроек

Имя файла - **storeland-uploader-config.json**

```javascript
{
    "SECRET_KEY": "d00bcfec8c1eb1ad355fed9fc068e32a",
    "SITE": "https://trialshop.storeland.ru"
}
```
