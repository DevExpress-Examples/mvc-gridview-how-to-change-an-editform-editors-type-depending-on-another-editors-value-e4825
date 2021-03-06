<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/WebSite/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/WebSite/Controllers/HomeController.vb))
* [Person.cs](./CS/WebSite/Models/Person.cs) (VB: [Person.vb](./VB/WebSite/Models/Person.vb))
* [PersonsList.cs](./CS/WebSite/Models/PersonsList.cs) (VB: [PersonsList.vb](./VB/WebSite/Models/PersonsList.vb))
* [MyScript.js](./CS/WebSite/Scripts/MyScript.js) (VB: [MyScript.js](./VB/WebSite/Scripts/MyScript.js))
* [GridViewPartial.cshtml](./CS/WebSite/Views/Home/GridViewPartial.cshtml)
* [Index.cshtml](./CS/WebSite/Views/Home/Index.cshtml)
<!-- default file list end -->
# MVC GridView - How to change an EditForm editor's type depending on another editor's value
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4825/)**
<!-- run online end -->


<p>This example demonstrates how to implement a scenario when an editor for a certain field changes its type (for example, from ComboBox to TextBox)  depending on the value in another editor.</p><p>Since it is impossible to bind two editors placed on one form to the same field (in this case, their Name property will be equal, which is forbidden), the HiddenField is used for storing values and transferring them to the server.</p>

<br/>


