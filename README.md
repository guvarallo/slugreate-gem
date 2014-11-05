# Slugreate

Create slugs for your application in a very robust and simple way.

* It uses the parameterize method

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

**Created by [Gustavo Varallo.](http://varallo.me)**

