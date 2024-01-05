# Chatbot over PDF using RAG

## Objective
Implement a chatbot that can answer the questions specific to any PDF.

## Description
Use any Large Language Model to create a basic chatbot that takes a PDF as argument and return answer based on the context from the pdf.
You can access the PDF from your folder, no need to integrate upload mechanism in the app.
**Use [**UG Rulebook**](https://www.iitb.ac.in/newacadhome/ugrulebook.pdf) to test your chat bot.
## Structure
- LLM model initialization
- Pdf loading and parsing
- Text splitter
- Vector database
- Searching and passing the context to the prompt
- Custom prompt passing to the model and processing the output
- Displaying output using UI

## Deliverables
No need to make a very complex chatbot. 
- A python script or a github repo or a Jupyter notebook or a colab notebook with the code.
- The code should have a basic UI.

## Resources 
- **GOOGLE**
- Youtube
- Chatgpt too, but sadly that will not be much of a help in case of langchain issues.

## Tips and advices

- Upload your project to github with a good readme file. (Other submition methods are also fine)

## If this project is too simple for you(lol)
**Totally Optional Challenges**
Out of the scope of this courses, just for fun and future enhancements.
Only for people who are very much interested.
- Make a conversational chatbot that retains a memory or
- Make a chatbot over pdf without landchain or
- Use an LLM model with 7b parameters or more in your model and code it in google colab(ps: Free version of colab will not have enough RAM to load 7b parameters, so you'll need to find a way to load it, without buying the premium ofcourse)
- Make the UI more beautiful and with more features like temperature slider and with an option to upload the pdf.