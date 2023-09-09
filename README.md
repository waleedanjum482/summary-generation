# summary-generation
Colab notebook is attached with this repo. 
The code is for the summarization of book content such that summary couldn't exceed more than 20 pages.
The summary is generated in such a way that first time summary is generated then this summary is again send to the model for second time, and second time generated is send to the model for the third time, so that fluency, readability can achieved.
The whole code will remain the same. Only the model for summary generation and its parameter will be replaced according to the model requirements.
A formula is written in model summary genertion code. which will help to generates the final summary which will not be more then 6000 words which will be less then 20 pages.
Then the final summary is converted into docx with good alignment and justification and fonts and converted into pdf so that user could have good reading experience.

