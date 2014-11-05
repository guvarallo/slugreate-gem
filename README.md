# Slugreate

Create slugs for your Rails application in a very robust and simple way.

* It uses Rails' [parameterize method.](http://api.rubyonrails.org/classes/ActiveSupport/Inflector.html#method-i-parameterize)

* It prevents URLs with the same name by appending numbers at the end.


## Installation

Add the following to your Gemfile:

```
gem 'slugreate'
```

In your application.rb file add:

```
require 'slugreate'
```

On the models you want to create the slugs, don't forget to include Slugreate:

```
include Slugreate
```

And add the method below on the model class, changing the 'ATTRIBUTE' name to whichever attribute of the class you want the slug to be created by:

```
slugable_column :ATTRIBUTE
```


<p align="center">
  <b>Created by <a href="http://varallo.me">Gustavo Varallo</a>. Enjoy!</b>
</p>


