# SciPosterHTML
Scientific Conference Posters in HTML+CSS+MathJax. Lightweight and no frills.

Do you want to create posters for scientific conferences using HTML+CSS? 
The SciPosterHTML repository contains real-life examples to get your started. 
You only need a webbrowser, a text editor, and some knowledge in HTML and CSS. 
No further installations and software required.

SciPosterHTML is not a library but a collection of hands-on examples. 
There is a very thin layer of abstraction. 
This is allows you to quickly understand the HTML+CSS code and modify it by your needs.

You can use this immediately wherever you have an editor and a webbrowser.

## How to 
Just edit sciposter.html and sciposter.css to your needs

## Motivation
SciPosterHTML is an alternative to writing printable scientific posters in LaTeX. 
There are numerous advantages of using HTML for posters:

- HTML has a very large community and many resources online
- HTML is a widely supported technology: you are already using it!
- HTML is very simple 
- HTML lets you fix font family and font sizes easily, you can easily control graphical elements (such as borders) and control the sizing of elements (e.g. via Flexbox)
- HTML even supports printing specifications via CSS
- Posters can easily adapt to different devices (print, laptop browser, mobile browser, ...)

You may also find this repository helpful if you are looking for an alternative to WYSIWYG software such as PowerPoint or LibreOffice Impress but refrain for the technical complexity of LaTeX. 

Conference posters are typically one-off projects:
there is generally no sequence of posters and little to no corporate design. 
Quite the opposite: you want your individual poster to stick out!
For that reason, SciPosterHTML is not a "library" to produce posters.
Instead, it is a collection of working examples that you can easily modify to your project.


## Known issues and workarounds

- You can print a PDF from your browser. 
However, the PDF file may not include all the fonts that your browser loads online. 
This has caused issues when trying to produce an A0 print in a printer studio. 
A work-around has been trying out different browsers: 
Chrome, Firefox, and MS Edge show different behaviors.

- Different browsers show different flex box behaviors when things are getting cramped. 
This seems to roughly correspond with the browsers' rendering engine (Blink, Gecko, Webkit, ...).
If there is an issue, you should try out different browsers. 
