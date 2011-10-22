CHINSTRAP
=================

Bootstrap is Twitter's toolkit for kickstarting CSS for websites, apps, and more. It includes base CSS styles for typography, forms, buttons, tables, grids, navigation, alerts, and more.

Chinstrap is Bootstrap, mutated to support Facebook app canvas pages.

To get started -- checkout http://toddsundsted.github.com/chinstrap/!


Usage
-----

You can use Chinstrap in one of two ways: just drop the compiled CSS into any new project and start cranking, or run LESS on your site and compile on the fly like a boss.

Here's what the LESS version looks like:

``` html
<link rel="stylesheet/less" type="text/css" href="lib/chinstrap.less">
<script src="less.js" type="text/javascript"></script>
```

Or if you prefer, the standard css way:

``` html
<link rel="stylesheet" type="text/css" href="chinstrap.css">
```

For more info, refer to the docs!


Developers
----------

We have included a makefile with convenience methods for working with the chinstrap library.

+ **build** - `make build`
This will run the less compiler on the chinstrap lib and generate a chinstrap.css and chinstrap.min.css file.
The lessc compiler is required for this command to run.

+ **watch** - `make watch`
This is a convenience method for watching your less files and automatically building them whenever you save.
Watchr is required for this command to run.


For More Information
--------------------

For more information, check out Bootstrap:

https://github.com/twitter/bootstrap


Authors
-------

The following two cats are responsible for Bootstrap.

**Mark Otto**

+ http://twitter.com/mdo
+ http://github.com/markdotto

**Jacob Thornton**

+ http://twitter.com/fat
+ http://github.com/fat

Todd Sundsted (http://github.com/toddsundsted) is responsible for the changes to create Chinstrap.


Copyright and license
---------------------

Copyright 2011 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
