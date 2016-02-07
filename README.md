### Updated a hook menu 
We don't need users to have an access to 'mysearch', have a menu item and do need an argument and title callback.

### Split layout and data logic levels

### Used a pager
What about a LARGE results set?

### Added 'no results' handling
 
### Added a test
TDD is cool! And it is better to know when the project going to fall apart.

### Replaced one-by-one node loading by loading them in single query.
One query faster then multiply. Maybe we should better to load here only titles with instead of full nodes for better performance
but it depends of specifics. From the other hand returning full nodes mysearch_dosearch() can be used in more general way and we are 
confident about any potential alters can impact the nodes.
 
### Used EntityFieldQuery instead of flat sql
It respects access system and filter passed arguments

### Added 'published' condition to the query
We don't want to show unpublished content. 

### Used render array instead of flat html
How somebody else can alter how it looks.

### Updated code style and comments
Stick to drupal code standards 