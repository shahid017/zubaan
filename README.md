# Version 1.0.3

Updates.
Package has been devided into four main classes. 
New functions are added such as Text to pdf, Text of Docx, Text to Speech, Word Frequency, etc.
word_cloud now takes an extra argument of plot=True or False. By default it’s true and the word_cloud function will generate a plot if set to false, it will return the word cloud object. The same is for the word_frequnecy function which is added in the 1.0.3 version.



# NlpHub

NlpHub is a wrapper around Spacy, NLTK and some other libraries simple NLP tasks. You can perform simple tasks with just 3 or 4 lines of code. NlpHub can perform basic NLP operations with less code and less hassle.

Installation
You can install NlpHub via pip. Write this command in terminal and voila, you have installed NlpHub.

    pip install NlpHub
   

It will auto install dependencies and you don't need to worry about anything.

# Import
To use NlpHub in your Jupyter notebook or python file, You can import it like this.

    from NlpHub import Annotators, Transformers, Convertors, Analyzers
    Convertors.txt_to_speech("your text here", save_to= "path_to_mp3_file" )

# Classes
There are four classes in NlpHub, Annotators, Transformers, Convertors, Analyzers.


# Annotators
This class contains all basic NLP operations which annotate document or words such as named_entity, Dependency etc.

## Functions
Annotators class has multiple functions that you can use. Some of them are explained here.

### Function 1 Annotators.sentiment()
Sentiment function accepts a string and do sentiment analysis using textblob library. Return str

### Function 2 Annotators.named_entity()
Named Entity function accepts a string and returns Named Entity dict with words as keys and their entity as values. Uses Spacy library

### Function 3 Annotators.dependency()
Dependency function accepts a string and returns dependency dictionary with words as keys and their dependency as values. Uses Spacy library


# Transformers
This class contains all basic NLP operations which transform document or words such as lemmatization or stemming etc.

## Functions
Transformers class has multiple functions that you can use. Some of them are explained here.

### Function 1 Transformers.lemma()
Lemmatization function accepts a string and return the lemmatized version of that input string.

### Function 2 Transformers.stem()
Stem function accepts a string and return the stemmed version of that input string.

### Function 8 Transformers.remove_sw()
Remove Stopwords function accepts a string and a optional stopword list  and return the string without any stopwords.


# Convertors
This class contains Text to Docx, Docx to text, text to pdf, pdf to text, text to speech functions.

## Functions
Convertors class has multiple functions that you can use. Some of them are explained here.

### Function 1 Convertors.txt_to_speech()
Text to speech accepts a text and converts into speech and save as mp3 file.

### Function 1 Convertors.txt_to_pdf()
Text to PDF accepts a string and a pdf file path and write that text to pdf.

# Analyzers
This class contains all basic NLP operations which transform and plot on data.

## Functions
Analyzers class has multiple functions that you can use. Some of them are explained here.

### Function 1 Analyzers.word_cloud()
Word Cloud fucntions accepts string and plot a word cloud or return word cloud object. The bigger a word, the more important it is.

### Function 2 Analyzers.word_frequency()
Word frequency fucntions accepts string, counts word occurances and plot a bar graph or returns dictionary of words with their occurances. 




# About Author
Hi there, My name is Muhammad Shahid and I am working as Data Scientist in Five Rivers Technologies. I have done BSCS from COMSATS University Islamabad and MSCS from NUCES FAST Islamabad. I have expertise in Data Science, Machine Learning(ML) and Natural Language Processing(NLP). If you have any query about this project, you may reach me at chshahidhamdam@gmail.com. Read about my journey here. 

www.muhammadshahid.techsandooq.com

https://www.linkedin.com/in/shahidsharif1/

https://www.facebook.com/shahid.hamdam/

