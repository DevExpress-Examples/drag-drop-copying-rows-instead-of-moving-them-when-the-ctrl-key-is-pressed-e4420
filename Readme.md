<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/Q453145/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/Q453145/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/Q453145/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/Q453145/MainWindow.xaml.vb))
<!-- default file list end -->
# Drag & Drop - Copying rows instead of moving them when the CTRL key is pressed


<p>This example demonstrates how to allow a user to copy dragged rows on the modifier key press. A custom attached property is used to determine whether or not the user wants to copy rows. You can adjust this property in the PreviewKeyDown and PreviewKeyUp event handlers. Then, use it in the DragElementTemplate to modify the drag element appearance accordingly. At last, replace data objects within the DraggedRows collection in the Drop event handler with newly created items.</p>

<br/>


