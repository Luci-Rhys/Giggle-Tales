**Giggle Tales**


This web application will harness the power of Generative AI to help users produce childrens story books.


Users can create an account, login, view and create stories. To create a story, the user will provide a story (text block). Our application will send the story with a prompt to a text-to-text model to break the story into pages that make logical sense. The output will be a delimited version of the story, with the delimiter in place of page breaks. Our application will process the output into pages, and then send each page to a text-to-image model with a prompt to generate the image for that page. The output image and the text for each page will be stored in our database, and users can view their stories (which are made up of pages) through their dashboard.


 
