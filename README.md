![example workflow](https://github.com/lekseff/CI_CD_Test/actions/workflows/test.yml/badge.svg)
![example workflow](https://github.com/lekseff/CI_CD_Test/actions/workflows/deploy.yml/badge.svg)

Правила сдачи задания:

1. **Важно**: в рамках этого ДЗ нужно использовать менеджер пакетов yarn (а значит, никакого `package-lock.json` в репозитории быть не должно)
2. **Важно**: всё должно собираться через Webpack (включая картинки и стили) и выкладываться на Github Pages через Appveyor.
3. В README.md должен быть размещён бейджик сборки и ссылка на Github Pages
4. В качестве результата присылайте проверяющему ссылки на ваши GitHub-проекты

---

### Игра с гоблинами

![](./pic/GracefulMiniatureBustard-small.gif)

#### Легенда

Вы решили доделать игру с гоблинами, поэтому нужно реализовать оставшуюся логику.

#### Описание

Нужно доделать игру с гоблинами, реализовав следующую логику:
1. Гоблин появляется в рандомной точке (набор точек фиксирован) ровно на 1 секунду
1. Если пользователь успел за это время кликнуть на этой точке (попробуйте сделать custom-курсор в виде молотка), то:
    * пользователю засчитывается +1 балл
    * гоблин пропадает из ячейки
1. Если пользователь пропустил 5 появлений гоблинов, то игра завершается.

Попробуйте реализовать всё не в виде единого скрипта, а разбив приложение на классы, каждый из которых ответственен за определённую логику.

Всё должно собираться через Webpack (включая картинки и стили) и выкладываться на Github Pages через CI.