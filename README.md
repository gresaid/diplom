## Редакторы

* [Русский словарь для
  TeXstudio](http://extensions.openoffice.org/en/project/dict_ru_RU_yo) —
  распакуйте файлы .dic и .aff из архива в любую папку, выбранную в настройках
  TeXstudio в закладке «General», пункт «Spelling Dictionary Directories», далее
  выберите ниже язык по умолчанию «russian_english».

## Утилиты

* [Утилита make](http://gnuwin32.sourceforge.net/packages/make.htm) для Windows
  (выполняет команды из файлов Makefile)
* [Online-конвертер latex->rtf](http://www.sciweavers.org/convert-latex-to-rtf)
* [Online-конвертер изображений в eps](http://www.converthub.com/)
* [Online LaTeX Table Generator](http://www.tablesgenerator.com/latex_tables)
* [Online LaTeX Formatter](https://c.albert-thompson.com/latex-pretty/)
* [Online LaTeX equation editor](https://www.codecogs.com/latex/eqneditor.php?lang=en-en)
* [LaTeX Cloud Compiler](https://latexonline.cc/)
* [Конвертер tiff->ps](http://www.libtiff.org/)
* [Конвертер jpeg->ps](http://www.pdflib.com/)
* [Конвертер
  eps->pdf](http://www.ctan.org/tex-archive/support/epstopdf/?action=/tex-archive/support/)
* [Конвертер tex->html](http://hutchinson.belmont.ma.us/tth/)
* [Конвертер latex->rtf](http://sourceforge.net/projects/latex2rtf/)
* [Конвертер OpenOffice->latex](http://writer2latex.sourceforge.net/)
* [Pandoc, конвертер множества форматов](http://pandoc.org/releases.html)

## Прочие полезные ссылки

* [ГОСТ 8.417–2002](http://hoster.bmstu.ru/~ms/normocontrol/gosts/8.417-2002.pdf)

## Сборка PDF из командной строки (Latex)

Сборку можно производить следующими командами:

* Дипломнная работа: `latexmk -pdf -pdflatex="xelatex %O %S" dissertation`

Либо можно использовать make-файлы (движок `xelatex`): из корневого
каталога выполнять

* `make` для сборки всего
* `make dissertation` для сборки дипломнная работы,
* `make presentation` для сборки презентации для доклада,
* `make dissertation-draft` для сборки дипломнная работы в режиме черновика,
* `make release` для сборки всего и внесения финальных *.pdf файлов в
  систему контроля версий git
* `make clean` очистка от временных файлов
* `make distclean` очистка всех генерируемых файлов (включая *.pdf*)
* `make pdflatex` сборка полной версии с движком `pdflatex` (несколько
  быстрее, чем `xelatex`, движок для библиографии в
  соответствии с настройками.
* 