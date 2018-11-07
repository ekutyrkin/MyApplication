# MyApplication
Простейший Android проект для генерации apk файла с требуемыми параметрами.
### Запуск
(заменить значения параметров)
```bash
gradle clean -Papp_uuid=00000001-0001-0001-0001-000000000001 -PapplicationId=com.example.test -PversionCode=10 build
```
.apk файл будет собран в: `app\build\outputs\apk\release`
