# autostart-detector

Детектор keylogger'ов и подозрительных автозагрузок для Windows на C# .NET 8.

## Возможности (план)

- скан ключей реестра: Run, RunOnce, Winlogon;
- проверка папок автозагрузки (Startup);
- службы и задания планировщика;
- детект глобальных хуков клавиатуры (признак keylogger'а);
- эвристики: неизвестные подписи, подозрительные пути;
- отчёт в JSON и HTML.

## Стек

- Язык: C# (.NET 8, Windows)
- Планируемые библиотеки: `Microsoft.Win32`, `System.Management`

## Сборка и запуск

```bash
dotnet build -c Release
dotnet run
```

## Лицензия

MIT
