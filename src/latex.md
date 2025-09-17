---
title: Оформление текста ВКР
subtitle: Сопровождение Научной Работы
---

# Правила оформления

::: columns
:::: {.column width=55%}

\onslide<3->

## \centering Пояснения

- Вспомогательные материалы
  - [Методические рекомендации](https://www.nsu.ru/n/mathematics-mechanics-department/documents/%D0%9C%D0%B5%D1%82%D0%BE%D0%B4%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8%20(%D0%BA%D1%83%D1%80%D1%81,%20%D0%92%D0%9A%D0%A0,%20%D0%B4%D0%BE%D0%BA%D0%BB%D0%B0%D0%B4%D1%8B).pdf)
  - [ГОСТ\ 7.32---2001](https://www.nsu.ru/n/mathematics-mechanics-department/documents/%D0%A1%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%20%D0%B8%20%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0%20%D0%BE%D1%84%D0%BE%D1%80%D0%BC%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F.pdf)
- Обложка и титульный лист
  - Оформляется по [шаблону](https://www.nsu.ru/n/mathematics-mechanics-department/documents/%D0%A2%D0%B8%D1%82%D1%83%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D0%BB%D0%B8%D1%81%D1%82%D1%8B%202018.doc)
- Реферат (аннотация)
  - \textcolor{CtpGreen}{Не требуется} на кафедре программирования
- Перечень условных обозначений
  - \textcolor{CtpGreen}{На ваше усмотрение}
- Основная часть
  - Поля: \textcolor{CtpRed}{как в указаниях}
  - Шрифт:
    \textcolor{CtpGreen}{любой} (обычно Times New Roman),
    \textcolor{CtpRed}{через два интервала},
    \textcolor{CtpRed}{14 кеглем}
- Список использованной литературы
  - [ГОСТ\ Р\ 7.0.5---2008](https://www.ifap.ru/library/gost/7052008.pdf)

::::

:::: {.column width=43%}

\onslide<2->

## \centering Правила оформления дипломной работы на ММФ

\centering

![](images/latex/mmf-thesis.png)

::::: columns
:::::: {.column width=80%}

```{=latex}
\begin{minipage}[c][.1\textheight][c]{\linewidth}
\centering \scriptsize
```
<https://www.nsu.ru/n/mathematics-mechanics-department/studentam/thesis/>
```{=latex}
\end{minipage}
```
::::::
:::::: {.column width=20%}

```{=latex}
\begin{minipage}[c][.1\textheight][c]{\linewidth}
\centering
\qrcode[height=1.2cm]{https://www.nsu.ru/n/mathematics-mechanics-department/studentam/thesis/}
\end{minipage}
```
::::::
:::::



::::
:::

# ГОСТ

. . .

> \centering ГОСТ --- Межгосударственный стандарт

. . .

## \centering Система стандартов по информации, библиотечному и издательскому делу

\vspace{0.5em}

. . .

- [ГОСТ\ 7.32---2001](https://www.nsu.ru/n/mathematics-mechanics-department/documents/%D0%A1%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%20%D0%B8%20%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0%20%D0%BE%D1%84%D0%BE%D1%80%D0%BC%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F.pdf)
  \small Отчет о научно-исследовательской работе. Структура и правила оформления
  - Содержит множество \textcolor{CtpGreen}{рекомендаций} по оформлению
  - На практике часто оформляют \textcolor{CtpRed}{не по ГОСТу}
    - Нумерацию перечислений
    - Формат сносок и листингов

. . .

- [ГОСТ\ Р\ 7.0.5---2008](https://www.ifap.ru/library/gost/7052008.pdf) 
  \small Библиографическая ссылка. Общие требования и правила составления
  - Есть поддержка во многих системах составления библиографии
    - Citation style language на [Zotero](https://www.zotero.org/styles?q=GOST)
    - Пакеты [gost](https://ctan.org/tex-archive/biblio/bibtex/contrib/gost?lang=en)
      и [biblatex-gost](https://ctan.org/pkg/biblatex-gost?lang=en) для \LaTeX

# В чем писать? {.fragile .t}

. . .

::: columns
:::: {.column width=35%}

## \centering Варианты

. . .

```{=latex}
\newcommand{\ihl}[2]{\textcolor<4->{#1}{#2}}
```

- \ihl{CtpRed}{Microsoft Word}
- \ihl{CtpRed}{Google Docs}
- \ihl{CtpGreen}{\LaTeX}
- \ihl{CtpGreen}{Pandoc (Markdown + \LaTeX)}
- \ihl{CtpGreen}{Typst}

. . .

. . .

<!-- Keep only footnote without its mark -->
`\only<5->{\sbox0{\footnote<5->[frame]{`{=latex}
[Инструментарий Современного Программиста: Языки разметки](https://github.com/nsu-syspro/mpt-slides/blob/master/publish/markup.pdf?raw=true)
`}}}`{=latex}

. . .

## \centering Примеры работ

- Master thesis 2018 (pandoc)
  - [GitHub](https://github.com/liontiger23/master-thesis-2018)
  - [pdf](https://github.com/liontiger23/master-thesis-2018/blob/master/publish/thesis.pdf?raw=true)
- PhD report 2021 (pandoc)
  - [GitHub](https://github.com/liontiger23/phd-report-2021)
  - [pdf](https://github.com/liontiger23/phd-report-2021/blob/master/publish/report.pdf?raw=true)

::::
:::: {.column width=65%}

. . .

## \centering Шаблоны

- [liontiger23/thesis-template-latex](https://github.com/liontiger23/thesis-template-latex)
  - \textcolor{CtpGreen}{Рекомендуемый} стартовый репозиторий для ВКР в \LaTeX
  - Два основных файла: преамбула и основной текст
  - Легко расширяется
  - Сборка через `make`
- [liontiger23/thesis-template](https://github.com/liontiger23/thesis-template)
  - Аналогичный репозиторий для ВКР в pandoc
  - Придется изучить не только \LaTeX, но и \textcolor{CtpRed}{особенности работы} pandoc
    и их \textcolor{CtpRed}{взаимодействия друг с другом}
- [AndreyAkinshin/Russian-Phd-LaTeX-Dissertation-Template](https://github.com/AndreyAkinshin/Russian-Phd-LaTeX-Dissertation-Template)
  - Довольно \textcolor{CtpRed}{громоздкий} шаблон для диссертаций
  - \textcolor{CtpGreen}{Рекомендуется} ознакомиться с отрендеренным
    [документом](https://github.com/AndreyAkinshin/Russian-Phd-LaTeX-Dissertation-Template/releases/download/v1.0.0/dissertation_lualatex_cmu_bibtex.pdf?raw=true),
    с множеством различных примеров, правил и особенностей оформления

::::
:::


# {.plain}

\centering
```{=latex}
{\fontsize{48pt}{7.2}\selectfont Q\&A }
```
