# Microsoft Tutorial: Create a web API with ASP.NET Core

This tutorial teaches the basics of building a controller-based web API that uses a database.
Another approach to creating APIs in ASP.NET Core is to create minimal APIs.


<table align="center">
<tr>
	<td><code>GET /api/todoitems</code></td>
	<td>Get all to-do items</td>
	<td>None</td>
	<td>Array of to-do items</td>
</tr>
<tr>
	<td><code>GET /api/todoitems/{id}</code></td>
	<td>Get an item by ID</td>
	<td>None</td>
	<td>To-do item</td>
</tr>
<tr>
	<td><code>POST /api/todoitems</code></td>
	<td>Add a new item</td>
	<td>To-do item</td>
	<td>To-do item</td>
</tr>
<tr>
	<td><code>PUT /api/todoitems/{id}</code></td>
	<td>Update an existing item &nbsp;</td>
	<td>To-do item</td>
	<td>None</td>
</tr>
<tr>
	<td><code>DELETE /api/todoitems/{id}</code> &nbsp; &nbsp;</td>
	<td>Delete an item &nbsp; &nbsp;</td>
	<td>None</td>
	<td>None</td>
</tr>
</table>

### Link for this tutorial
https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-8.0&WT.mc_id=dotnet-35129-website&tabs=visual-studio