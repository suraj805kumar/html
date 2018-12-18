# html

<!DOCTYPE> declaration to your HTML documents, so that the browser knows what type of document to expect.

<!DOCTYPE html>, html5 doctype is not case sensitive.

Either one of these three will work:

1) <!DOCTYPE html>
2) <!DOCTYPE HTML>
3) <!doctype html>


The <html> element is the root element of a document. Every document must begin with this element, and it must contain both the <head> and  <body> elements.

It is considered good practice to specify the primary language of the document on this element using the lang attribute.

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Hello World</title>
    </head>
    <body>
        <h1>Hello World</h1>
        <p>
            First HTML Page.
        </p>
    </body>
</html>





Reference:

https://dev.w3.org/html5/html-author/#doctype-declaration
