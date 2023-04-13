<!-- default badges list -->
<!-- default badges end -->
# DataGrid for .NET MAUI - Search Bar

This example shows how to implement a [Data Grid](https://docs.devexpress.com/MAUI/403255/data-grid/data-grid) search. The search bar is placed into the page's [toolbar area](https://learn.microsoft.com/en-us/dotnet/api/microsoft.maui.controls.toolbaritem).

<img width="30%" src="https://user-images.githubusercontent.com/12169834/230120654-1b2536ff-757a-499b-873b-5eb5d13b47ad.png"/>

## Implementation Details

* The [TextEdit](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.TextEdit) control is placed in the title bar. You can specify the [EndIcon](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.EditBase.ErrorIcon) property to define the right icon. 
* Specify the [PlaceholderText](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.EditBase.PlaceholderText) property to define TextEdit's placeholder text. Define the [PlaceholderColor](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.EditBase.PlaceholderColor) property to specify the color of placeholder text.
* You can use the [ClearIconColor](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.EditBase.ClearIconColor) property to define a color of TextEdit's clear icon.
* On the [TextChanged](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.TextEditBase.TextChanged) event, you can define a query parameter and pass it to the [DataGridView.FilterString](https://docs.devexpress.com/MAUI/DevExpress.Maui.DataGrid.DataGridView.FilterString). Refer to the following topic for more information on the filter criteria syntax: [Criteria Language Syntax](https://docs.devexpress.com/CoreLibraries/4928/devexpress-data-library/criteria-language-syntax).


## Files to Look At

* [MainPage.xaml](CS/MainPage.xaml)
* [MainPage.xaml.cs](CS/MainPage.xaml.cs)
* [Styles.xaml](CS/Resources/Styles/Styles.xaml)

## Documentation

* [Featured Scenario: Search Bar](https://docs.devexpress.com/MAUI/404301)
* [Featured Scenarios](https://docs.devexpress.com/MAUI/404291)
* [Data Grid for .NET MAUI](https://docs.devexpress.com/MAUI/403255/data-grid/data-grid)
* [TextEdit](https://docs.devexpress.com/MAUI/DevExpress.Maui.Editors.TextEdit)

## More Examples

* [DevExpress Data Grid for .NET MAUI](https://github.com/DevExpress-Examples/maui-data-grid/)
* [DevExpress Mobile UI for .NET MAUI](https://github.com/DevExpress-Examples/maui-demo-app/)
