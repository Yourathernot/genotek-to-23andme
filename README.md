# genotek-to-23andme
Парсер исходных данных результата ДНК-теста Genotek в формат 23AndMe

## Общая информация
Данный проект предназначен для конвертации из формата vcf, который Genotek 
предоставляет бесплатно, в платный формат 23AndMe (3, 4 или 5 версии)

## Использование
Поместить [genome.bd](genome.bd) и [genotek.exe](https://github.com/Yourathernot/genotek-to-23andme/releases/download/1.0/genotek.exe) в одну папку
Запустить командную строку и перейти в эту папку

```shell
# Варианты использования
genotek -vcf [путь vcf файла]
genotek -vcf [путь vcf файла] -output [путь выходного файла]
genotek -vcf [путь vcf файла] -output [путь выходного файла] -version [3/4/5]

# Помощь
genotek -h

# Пример
genotek -vcf example.vcf -output 23AndMeGenotek.txt -version 3
```

## Лицензия
[MIT](LICENSE)
