# Intellij IDEA Preferences

Fonts I use :

- FiraCode : [https://github.com/tonsky/FiraCode](https://github.com/tonsky/FiraCode)
- Hasklig : [https://github.com/i-tu/Hasklig](https://github.com/i-tu/Hasklig)
- Cascadia : [https://github.com/microsoft/cascadia-code](https://github.com/microsoft/cascadia-code)

To apply preferences:

```cmd
cd %appdata%\JetBrains\IntelliJIdea*
del /S /Q *
for /d %x in (*) do @rd /S /Q "%x"
git clone https://github.com/adiberr/Intellij-IDEA-Preferences.git . --branch v2020.1
```
