Multiple FluentIcons in a FluentDataGrid lead to very slow repaint (250ms and higher).

The repro contains two pages that are identical, except one page has a FluentButton with a FluentIcon in each data grid row (performance issue) and the other page has a FluentButton with text in each data grid row (ok).

The delete buttons in the repro toggle the visibility of a loading indicator so the performance issue is visible directly.

[See this issue.](https://github.com/microsoft/fluentui-blazor/issues/370)
