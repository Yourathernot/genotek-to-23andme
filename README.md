# genotek-to-23andme
Парсер исходных данных результата ДНК-теста Genotek в формат 23AndMe

## Общая информация
Данный проект предназначен для конвертации из формата vcf, который Genotek 
предоставляет бесплатно, в платный формат 23AndMe (3, 4 или 5 версии)

## Использование
Поместить [genome.bd](genome.bd) и [genotek.exe] в одну папку

```shell
# Варианты использования
genotek -vcf [название vcf файла]
genotek -vcf [название vcf файла] -output [название выходного файла]
genotek -vcf [название vcf файла] -output [название выходного файла] -version [3/4/5]

# Помощь
genotek -h

# Пример
genotek -vcf example.vcf -output 23AndMeGenotek.txt -version 3
```

## Лицензия
[MIT](LICENSE)
