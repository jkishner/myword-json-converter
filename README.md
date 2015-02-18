# myword-json-converter
This is a form that outputs JSON to feed into [myWord](https://github.com/scripting/myWord)

[See it in action.](http://javascript.jeffreykishner.com/myword-json-converter.html)

More info TK. For now, [read this blog post](http://thoughts.jeffreykishner.com/a-simple-form-for-publishing-to-myword-io).

To Do
=====

* enable localStorage for `authorname`, `authorwebsite`
* simplify script by using JSON.stringify instead of adding quotes, colons and brackets to `output` variable

Update
======

**2015-02-13**

* added the following attributes: `authorwebsite`, `description`, `titlefont`, `bodyfont`, `flMarkdown`
* provided default black background image if `img` is not entered

**2015-02-18**

* Using [myjson.com api](http://myjson.com/api) to write json directly to the service (for free hosting)

