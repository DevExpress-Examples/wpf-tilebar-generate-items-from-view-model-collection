<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128641783/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T148752)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/TBExample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/TBExample/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/TBExample/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/TBExample/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Bind TileBar to a Collection of Items


To use [TileBar](https://documentation.devexpress.com/WPF/115595/Controls-and-Libraries/Navigation-Controls/Tile-Bar) according to the MVVM pattern, you can generate TileBarItems from a collection. To accomplish this task, assign a collection to the **TileBar.ItemsSource** property. 

To change properties of generated [TileBarItems](https://documentation.devexpress.com/#WPF/clsDevExpressXpfNavigationTileBarItemtopic), use the **TileBar.ItemContainerStyle** property. 

If you want to build a multi-level hierarchy, put the TileBar into [TileBarItem.FlyoutContentTemplate](https://documentation.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileBarItem.FlyoutContentTemplate.property).
<!-- feedback -->
## Does This Example Address Your Development Requirements/Objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-tilebar-generate-items-from-view-model-collection&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-tilebar-generate-items-from-view-model-collection&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
