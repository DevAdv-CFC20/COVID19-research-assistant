
# Phase one: 

# Data analysis: clean the data from JSON files based on text-only:

The new output data can be found in the box, the share link here: https://ibm.box.com/s/8xeikvflfndb00hgg61ycqnp83amy3te
In the share link, we will find two different zip folders which we have used for:
The txt output is used for reading Abstract to extract questions for quieres.  
The html output is the uploaded data into Discovery. 

we are extracting articles “full-text article” from JSON files and save the results in the form of Txts \ Html.
Because Watson Discovery limit with 50k characters for every single document, the provided datasets “JSON files” are more than 50k characters. Therefore, We have applied this simple py script to extract “full-text article” from JSON files and save the results in the form of TXT \ HTML.

In our case, we have saved the results in HTML format, because WD doesn’t support Txt format. WD only supports document formats like pdf, word, excel, PowerPoint, Html, png, jpeg, and JSON.

The script does; Each executed file formatted like the following order:

- title

- abstract

- full-text article

This task helped us to have clear data formatted as a text document, it will be easy to manage the data capacity, and it will be easy to train our queries into Watson Discovery machine learning. Consequently, we will have accurate better results for our model.


