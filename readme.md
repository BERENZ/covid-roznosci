# Repozytorium z różnościami poświęconymi COVID-19 w Polsce

## Analiza ognisk 

+ [Małopolska](notebooks/1-malopolska.Rmd) -- ponieważ mają raporty w PDF, które są tabelami


## Autor

dr Maciej Beręsewicz
Adiunkt, Katedra Statystyki
Uniwersytet Ekonomiczny w Poznaniu
al. Niepodległości 10 | 61-875 Poznań
www.ue.poznan.pl    

## Pakiety

```
library(tidyverse)
library(rvest)
library(httr)
library(lubridate)
library(janitor)
```
oraz

[Tabula](https://github.com/tabulapdf/tabula)

## Sesja R

```
> sessionInfo()
R version 3.6.1 (2019-07-05)
Platform: x86_64-apple-darwin15.6.0 (64-bit)
Running under: macOS Catalina 10.15.6

Matrix products: default
BLAS:   /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib
LAPACK: /Library/Frameworks/R.framework/Versions/3.6/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
```

