# Symphony Community Site

## HTML Templates

This markup library contains the XML, XSLT and HTML used to build the templates for the Symphony community site. It is being maintained as a [Git repository on GitHub](https://github.com/bauhouse/getsymphony-html).

### Preprocessing HTML

XSLT is being used as a preprocessor (using xsltproc) to output valid, well-formed XHTML structure. This process of static site generation should be easy to manage on any Unix-based system (Mac, Linux) without having to install any software. On Windows, install xsltproc.

To process HTML, run the `./build` script in the same directory as this README file.

To process individual files, open the `workspace/build` file and find the xsltproc command referring to the HTML file you would like to process and run the command.

### Design Templates

The page layouts can be viewed in a browser at the following URLs: 

* http://bauhouse.github.com/getsymphony-html/
* http://bauhouse.github.com/getsymphony-html/discussions/
* http://bauhouse.github.com/getsymphony-html/discussions/post/
* http://bauhouse.github.com/getsymphony-html/questions/
* http://bauhouse.github.com/getsymphony-html/blog/
* http://bauhouse.github.com/getsymphony-html/showcase/
* http://bauhouse.github.com/getsymphony-html/events/
* http://bauhouse.github.com/getsymphony-html/about/
