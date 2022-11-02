# Song-Writing-Machine
The aim of this project is to develop a system that understands natural language and the structure of phrases and learns from a variety of song lyrics, in order to automatically generate original coherent lyrics.<br/>
The objectives of this project are: <br/>
* Collect lyrics of different artists in English to train the system on, which allows it to learn a wide range of vocabulary and a variety of song structures.
* Analyse the datasets collected or found and remove any irrelevant text that does not contribute to the meaning, such as words and characters from other languages and empty rows.
* Allow the user to provide details on the options for generating the lyrics, such as generating based on genre or an artist which the user picks.
* Apply data cleaning and processing techniques to break the raw data into small chunks and turn it into tokens that can be fed to the model.
* Build [Language Models](https://en.wikipedia.org/wiki/Language_model) that take the cleaned data as input, learn the words and the structure of the sentences, and finally generate original lyrics.
* Evaluate the results of the Language Model against the gold standard which is the artists’ lyrics.
