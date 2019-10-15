# Authenticated User - Layout Snippet

Snippets are Layout Elements that you can drag n drop into the layout canvas. You add them to the `Views/Elements` folder of your theme and they have to end with Snippet.cshtml. 
With this Snippet you can make a Page accessible only for authenticated users.

You have to add `AuthenticatedUserSnippet.cshtml` and `AuthenticatedUserSnippet.txt` files to your `Views/Elements` folder of your theme. After this you can drag the AuthenticatedUser snippet wherever you want and if the user is not logged ln will be redirected to a custom url or to login page.

Read more [here](https://medium.com/@george.roubie/orchard-cms-authenticated-user-layout-snippet-398993ee8464)
