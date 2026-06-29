# Навигация по практическим работам (Docker)

В данном репозитории содержатся выполненные практические задания по сборке контейнеров и написанию Dockerfile для различных технологических стеков (от простых консольных скриптов до компилируемых TUI-приложений на C++).

## 🚀 Перечень практических заданий

| # | Название каталога | Технологический стек | Описание задания | Переход к описанию |
| :--- | :--- | :--- | :--- | :--- |
| 1 | hello-world | Alpine Linux / Bash | Минимальный базовый образ, вывод строки в консоль. | [Перейти](./Dockerfile/hello-docker/hello-docker.md) |
| 2 | my-website | Nginx / HTML5 | Статический сайт на веб-сервере с монтированием томов (Volumes). | [Перейти](./Dockerfile/nginx/my-site.md) |
| 3 | my-python-app | Python (Slim) | Простое консольное приложение на интерпретируемом языке. | [Перейти](./Dockerfile/Python/Python.md) |
| 4 | simple_flask_app`| Python / Flask | Микрофреймворк, проброс портов и проверка эндпоинта `/health. | [Перейти](./Dockerfile/Flask+Python/Flask+Python_Mini.md) |
| 5 | MyApp | C# / .NET 8.0 (Web) | Многоэтапная сборка (Multi-stage) веб-сервиса ASP.NET Core. | [Перейти](./Dockerfile/dotNet/dotNet.md) |
| 6 | cpp-docker | C++ / GCC / Alpine | Статическая компиляция бинарного файла и запуск в Alpine. | [Перейти](./Dockerfile/cpp/cpp.md) |
| 7 | cpp-ftxui | C++ / CMake / FTXUI | Интерактивное консольное меню с библиотекой FTXUI на базе Ubuntu. | [Перейти](./Dockerfile/FTXUI/FTXUI.md) |
| 8 | ftxui-wow | C++ / CMake / Threads | Анимированный Gauge (прогресс-бар) в контейнере, многопоточность. | [Перейти](./Dockerfile/ftxui_wow/ftxui_wow.md) |
