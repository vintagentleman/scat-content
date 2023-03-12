# SCAT

This repository contains the source texts comprising the Saint Petersburg Corpus of Hagiographic Texts (SCAT) —
an electronic corpus of Old Russian hagiographic literature developed at Saint Petersburg State University.

The Russian hagiographic texts of the 15–17 centuries exhibit an exceptional richness of the language.
It is during this period that their abundant phraseology solidified into standard idioms, which wordsmiths would artfully adapt to the genre canon.
In many different ways, the language of hagiography influenced the development of literary Russian at that time.
The corpus aims to represent that language as faithfully as possible.

## Texts

| ID | Title | Century | Tokens | Bibliographical source |
|---|---|---|---|---|
| `AKush` | Житие Александра Куштского | 17th | 5K | БАН, Арханг., Д. 235 |
| `AKush-EvSzh` | Житие Александра Куштского и Евфимия Сянжемского | 18th | 2.5K | ИРЛИ, древлехранилище им. В. И. Малышева, оп. 23, 322 |
| `AndTtm` | Житие Андрея Тотемского | 18th | 2K | РНБ, Колобова 189 |
| `AntSij` | Житие Антония Сийского | 16th | 33K | РНБ, Q. I. 22 |
| `ArsKml` | Житие Арсения Комельского | 18th | 5.5K | РНБ, Пог. 647 |
| `ASvir` | Житие Александра Свирского | 16th | 21K | РНБ, Пог. 874 |
| `CrlNvz` | Житие Кирилла Новоезерского | 17th | 15K | РНБ, Кир.-Бел. 66/1305 |
| `DGlush` | Житие Дионисия Глушицкого | 16th | 11K | РНБ, Соф. 438 |
| `DmPrlc` | Житие Димитрия Прилуцкого | 16th | 6K | РНБ, Соф. 1361 |
| `GrPelsh` | Житие Григория Пельшемского | 16th | 7K | РНБ, Пог. 853 |
| `GrsVlg` | Житие Герасима Вологодского | 18th | 4K | РНБ, Пог. 647 |
| `IgnLm` | Житие Игнатия Ломского | 18th | 6K | РНБ, Колобова 643 |
| `IgnVlg` | Житие Игнатия Вологодского | 18th | 2K | РНБ, Пог. 647 |
| `InnKml` | Житие Иннокентия Комельского | 18th | 1K | РНБ, Пог. 647 |
| `IoaKam` | Житие Иоасафа Каменского | 17th | 10K | РНБ, Солов. 227/227 |
| `KrnKml` | Житие Корнилия Комельского | 17th | 13K | РНБ, Пог. 787 |
| `KsUgl` | Житие Кассиана Угличского | 17th | 2K | РНБ, Пог. 1563 |
| `PObn` | Житие Павла Обнорского (житие) | 16th | 9K | РНБ, Пог. 659 |
| `PObn-m` | Житие Павла Обнорского (чудеса) | 16th | 8K | РНБ, Соф. 1470 |
| `SrgNurm` | Житие Сергия Нуромского | 16th | 14K | РНБ, Соф. 1470 |
| `StKml` | Житие Стефана Комельского | 17th | 3.5K | РНБ, ОЛДП, Q. 198 |
| `ThdTtm` | Житие Феодосия Тотемского | 18th | 5K | ВОКМ, 2011 |
| `VsTix` | Житие Вассиана Тиксненского (житие и чудеса 1–8) | 18th | 3K | РНБ, Колобова 189 |
| `VsTix-m` | Житие Вассиана Тиксненского (чудеса 9–29) | 18th | 3K | ГАВО, ф. 883, оп. 1, д. 233 |

## Formats

| Directory | Description | Format | # of texts |
|---|---|---|---|
| [`raw`](./raw) | Raw texts as they were initially transcribed | Plain text, in **Windows 866** encoding | 24 |
| [`annotation/structural`](./annotation/structural) | Texts enriched with annotation of structural units, such as chapters and quotations | Plain text with XML injections | 6 |
| [`annotation/morphological`](./annotation/morphological) | Texts with morphological annotation (in a custom format with Cyrillic tags) | TSV | 7 |
| [`annotation/combined`](./annotation/combined) | Texts with both morphological and structural annotation | TSV with XML injections | 6 |

On our releases page, you can find `.zip` archives with all texts converted to [TEI XML](https://tei-c.org/),
as well as binary `.txm` files which can be imported into [TXM](https://txm.gitpages.huma-num.fr/textometrie/en/index.html).

## Copyright

This corpus is licensed under CC-BY-SA-4.0.
