# Регулятор освещенности

_[Курсовой проект. 3 курс, 2 семестр. Теория автоматизированного управления]_

Репозиторий содержит схемы (принципиальные и рабочие) всех частей регулятора, а также задачи по части схемотехнического моделирования, разводки, физического проектирования и разработки макетной платы, задачи по уточнению задания и т.д. Теория по задаче описана в отчете (`/doc`) и в WIKI проекта.

## Структура репозитория

Структура и требования к оформлению репозиторев приведены в [соответствующем разделе](https://dqxl1t0aqaave4.gitbooks.io/wiki/content/code/repos.html) WIKI.

За подробностями следует обращаться к `README.MD` соответствующих директорий.

## Работа с репозиторием

Исходя из того, что

1. Репозиторий содержит управляемые `Git LFS` директории
2. Репозиторий включает в свой состав подмодули (submodules)

клонирование репозитория несколько осложнено, хотя и не сильно.

Во-первых, на рабочих машинах, кроме самого `git`, должен быть установлен `Git LFS`. При выкачивании любых изменений он автоматически подхватит из своей `CDN` требуемые файлы.

Во-вторых, при клонировании следует учитывать наличие подмодулей:

```bash
git clone --recurse-submodules https://github.com/Dqxl1t0AQAave4/act-photo.git
```
