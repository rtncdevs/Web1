# Web1
## Test for Prose.io

### Another heading

This is a small file to test out the Prose.io application, to look to see how it  may be used with Jekyll for instance.

- Some item 1
- Some item 2
- Some item 3

![nc-logo.jpg]({{site.baseurl}}/nc-logo.jpg)

If, like me, you are interested only in mapping entity coming from an other database (an erp in my case) to relate them to entities specific

of your application, then you can use the views as you use a table (map the view in the same way!). Obviously, if you try to update that entities, you will get an exception if the view is not updatable. The procedure is the same as in the case of normal (based on a table) entities:

Create a POCO class for the view; for example FooView
Add the DbSet property in the DbContext class
Use a FooViewConfiguration file to set a different name for the view (using ToTable("Foo"); in the constructor) or to set particular properties






