
# Phase one: 

# Data analysis: clean the data from JSON files based on text-only:

we are extracting articles “full-text article” from JSON files and save the results in the form of Txts \ Html.
Because Watson Discovery limit with 50k characters for every single document, the provided datasets “JSON files” are more than 50k characters. Therefore, We have applied this simple py script below to extract “full-text article” from JSON files and save the results in the form of TXT \ HTML.

In our case, we have saved the results in HTML format, because WD doesn’t support Txt format. WD only supports document formats like pdf, word, excel, PowerPoint, Html, png, jpeg, and JSON.

The script below does; Each executed file formatted like the following order:

title
abstract
full-text article

This task helped us to have clear data formatted as a text document, it will be easy to manage the data capacity, and it will be easy to train our queries into Watson Discovery machine learning. Consequently, we will have accurate better results for our model.


