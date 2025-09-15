# Презентации курса Сопровождение Научной Работы

Отрендеренные презентации находятся в директории [publish](publish):

- [Оформление текста в LaTeX](publish/latex.pdf)

## Building

Following command builds your presentations into `.pdf`:

```
make
```

## Publishing

To "publish" the final `.pdf` you can use the following command which builds and copies `src/*.pdf` into `publish/*.pdf`
which can then be committed to the repo:

```
make publish
```
