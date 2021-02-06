<!--
author:   Your Name

email:    your@mail.org

version:  0.0.1

language: en

narrator: US English Female

comment:  Try to write a short comment about
          your course, multiline is also okay.

attribute: This LiaScript macro is based on the implementation of [Bowserinator](https://github.com/Bowserinator/Periodic-Table-JSON). The original example can be found at [CodePen](https://codepen.io/aardrian/pen/NmoQdN).

PeriodicTable: @PeriodicTable.withStyle("width: 100%; height: 600px; border: 0; overflow: hidden;")

PeriodicTable.withStyle: <iframe src="https://liatemplates.github.io/PeriodicTable/index.html" style=@0></iframe>

-->

# Periodic Table Template

A simple template for visualizing an interactive periodic table.

__Try it on LiaScript:__

https://liascript.github.io/course/?https://raw.githubusercontent.com/LiaTemplates/PeriodicTable/main/README.md#1

__See the project on Github:__

https://github.com/LiaTemplates/PeriodicTable

Just include the macro in your `import` statement and call `@PeriodicTable` or `@PeriodicTablewithStyle()`

`import: https://github.com/LiaTemplates/PeriodicTable/blob/main/README.md`

```
@PeriodicTable


@PeriodicTable.withStyle("width: 50%; height: 600px;")
```

@PeriodicTable

--------

@PeriodicTable.withStyle("width: 50%; height: 600px;")

This LiaScript macro is based on the implementation of [Bowserinator](https://github.com/Bowserinator/Periodic-Table-JSON). The original example can be found at [CodePen](https://codepen.io/aardrian/pen/NmoQdN).
