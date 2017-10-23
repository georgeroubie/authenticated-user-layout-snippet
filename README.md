# Authenticated User - Layout Snippet

Snippets are Layout Elements that you can drag n drop into the layout canvas. You add them to the Views folder of your theme and they have to end with Snippet.cshtml. 
With this Snippet you can make a Page accessible only for authenticated users.

You have to add `AuthenticatedUserSnippet.cshtml` and `AuthenticatedUserSnippet.txt` files to your `Views/Elements` folder of your theme. After this you can drag the AuthenticatedUser snippet wherever you want and if the user is not Logged In will be redirected to another page.

For more Orchard Tricks: https://orchardtricks.dotnest.com
