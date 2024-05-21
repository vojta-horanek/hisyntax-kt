# hisyntax-kt
Kotlin syntax highliting for [OpTeX](https://github.com/olsak/OpTeX).

## Usage
At the beginning of your document, include the macro:
```tex
\input hisyntax-kt.opm
```
Then choose the syntax highlighter in your verbatims:
```tex
\begtt \hisyntax{kt}
...your kotlin code...
\endtt
```
Using `\hisyntax{kotlin}` is also possible.

## Example

To get a quick overview of the style, you can use the `example.tex` file in this repository.
The screenshot bellow shows what the compiled document should look like.
<img width="455" alt="example" src="https://github.com/vojta-horanek/hisyntax-kt/assets/12630566/10f302bb-a737-4c09-82ba-fd86987e6011">

## Licence

This software is in public domain.
