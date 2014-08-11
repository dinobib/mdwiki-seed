---
title: What's Jekyll?
---

[Jekyll](http://jekyllrb.com) is a static site generator, an open-source tool for creating simple yet powerful websites of all shapes and sizes. From [the project's readme](https://github.com/mojombo/jekyll/blob/master/README.markdown):

  > Jekyll is a simple, blog aware, static site generator. It takes a template directory [...] and spits out a complete, static website suitable for serving with Apache or your favorite web server.[^somesamplefootnote] This is also the engine behind GitHub Pages, which you can use to host your project’s page or blog right here from GitHub.

[^somesamplefootnote]: Here is the text of the footnote itself.

It's an immensely useful tool and one we encourage you to use here with Hyde.

Find out more by [visiting the project on GitHub](https://github.com/mojombo/jekyll).

~~~ ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
~~~


| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | _Closes_ a window     | 



Let's cite a fake book.

[#fake]: John Doe. *A Totally Fake Book*. Vanity Press, 2006.

Let's reference a glossary term.[^glossary]

[^glossary]:**Apple    :**

    Pomaceous fruit of plants of the genus Malus in 
    the family Rosaceae.

    Also the makers of really great products.

Here is some text containing a footnote.[^somesamplefootnote]

[^somesamplefootnote]: Here is the text of the footnote itself.
