# Превращаем VSCode в WebStorm

Бесплатно и сердито

Если вы еще не скачали VSCode: https://code.visualstudio.com

1. **Качаем шрифты**  
   JetBrains Mono: https://www.jetbrains.com/lp/mono/  
   Ctrl + , (запятая) => {  
   Editor: Font Family => JetBrains Mono  
   Editor: Font Size => 13  
   }

2. **Расширения**

- [_Rider_](https://marketplace.visualstudio.com/items?itemName=EdwinSulaiman.jetbrains-rider-dark-theme) / [WebStorm](https://marketplace.visualstudio.com/items?itemName=xr0master.webstorm-intellij-darcula-theme) - Внешний вид
- [_JetBrains Icon Theme_](https://marketplace.visualstudio.com/items?itemName=chadalen.vscode-jetbrains-icon-theme) - Иконки из WebStorm
- [_Jest Runner_](https://marketplace.visualstudio.com/items?itemName=firsttris.vscode-jest-runner) - Для быстрого запуска проекта
- [_GitLens_](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Клиент Git
- [_Git Graph_](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) - Расширение, позволяющее в удобном графовом формате отслеживать изменения в проекте
- [_ESLint_](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Утилита позволяющая анализировать написанный код
- [_TSLint_](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin) - Утилита для анализа кода TypeScript
- [_Prettier_](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Расширение для форматирования кода по установленным правилам
- [_Auto Rename Tag_](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Автоматически переименование тегов в разметке HTML
- [_Auto Import_](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport) - Автоматический импорт
- [_Parameter Hints_](https://marketplace.visualstudio.com/items?itemName=DominicVonk.parameter-hints) - Показывает имя параметра вызываемой функции  
  /**_Дополнительно_**/
- [_Angular Language Service_](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - расширение для работы с Angular проектами
- [_REST Client_](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) - Очень удобная утилита, позволяет отправить HTTP-запрос, получить ответ с сервера и посмотреть его в VS Code
- [_indent-rainbow_](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) - Раскрашивает отступы перед кодом
- [_Better Comments_](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) - Плагин для стилизации комментариев (по ссылке есть примеры)

3. **Горячие клавиши**  
   Попользовавшись WebStorm нашел некоторые ХотКеи, которые удобнее VSCode'овских и перенес их сюда:

- CTRL + S => Сохранить все файлы (Удобнее сохранять все файлы сразу, а не прожимать CTRL + SHIFT + S)
- F4 => Сборка проекта (Run Task) (Выбираем нужный проект и с помощью хоткея быстро начинаем сборку)
- ALT + ЛКМ - Установить несколько курсоров

4. **Полезные фишки**  
   Также есть полезные фишки, которые по стандарту отключены в VS Code

- Auto Save => onWindowChange - Автосохранение файлов, когда вы переключились с редактора на другое окно, например браузер.
- Import Module Specifier => project-relative - Будет использоваться неотносительный импорт, только если путь неотносительного импорта выходит за пределы каталога проекта.
- "editor.formatOnSave": true, => вставляется в JSON параметров и каждый раз при сохранении файлов, код будет форматироваться.
