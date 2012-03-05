Compass and Bootstrap 2.0 on Rails
============================

Ever want to use Bootstrap 2.0 on Rails? (It has been out for at least 48 hours.)

Want to use compass? BAM.

In your gem file, do these things:

```
gem "compass-rails", ">= 0.12"
gem "bootstrap-sass", ">= 2.0"
```

In your application.scss import bootstrap using sass, not sprockets. 

```
@import "bootstrap";
@import "bootstrap-responsive";
```

I wish it were more interesting, but Chris Eppstein made compass drop dead simple to integrate.

Props
=====
* [Compass](http://compass-style.org)
* [Compass-Rails](https://github.com/Compass/compass-rails) enabled the asset pipeline
* [Bootstrap](http://twitter.github.com/bootstrap) from Twitter
* [Bootstrap-Sass](https://github.com/thomas-mcdonald/bootstrap-sass) gem

Author
-----
[Jesse Wolgamott](http://jessewolgamott.com), [@jwo](http://twitter.com/jwo)

I obviously did not write Rails, Compass, or Bootstrap

Copyright
========
MIT License
