# godot-4.2-rc5-theme-type-variation-regression

`main.tscn` has a `PanelContainer` and `Label` nested under a `Control` that implements theme.
There is a theme type variation applied to each. These have regressed in Godot `4.2-rc5` since `4.1.1`.
