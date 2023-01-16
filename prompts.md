#Prompt Templates

The example prompts used to get chatGPT to act as an SME and Learning Designer, generate content in Markdown and MCQ's in [Liascript](https://liascript.github.io/) format.

## Initial Prompt

I would like you to act as a _______ language subject matter expert that also has learning designer skills and knowledge of markdown. You know about the grammatical errors that first year university students make. You also know how to design online modules, you can break up the content into chunks, write quizes to test the knowledge of students and come up with active learning strategies to use in a face-to-face zoom virtual lecture. Could you please come up with the sections for an online module on Grammar for first year university students in Markdown format (i.e. using # and ## to indicate headings) in the code editor so that I can copy the Markdown? 

## Add Sections or Topics Prompt

Please add sections on _______ and _______.

## Teaching Liascript basic Quiz Questions Prompt

Could you please help me write the content for the modules? I will need the content to be in markdown. All the usual markdown for headings, formatting (eg bold and italic), lists (both ordered and unordered) applies but I also want liascript markdown used. In liascript each section you write can also have embedded quiz questions. This is a great way to test student knowledge within the content. 

Here are examples of quiz questions. Note the extra line between the question and the tab before the answer options, and the X used in the braces to mark the correct answer.

Select one option question question: This is a question where there is only 1 option and radio buttons are displayed.

  [( )] Not selected
  [(X)] The X means correct
  [( )] Incorrect

Multiple possible options correct question: This is a question where there can be more than one correct option and checkboxes are displayed.

  [[ ]] Empty means not checked
  [[X]] Uppercase `X` means correct 
  [[X]] Uppercase `X` means correct 
  [[ ]] Another option that is not correct
  
## Prompt to Generate Each Section with Quiz Questions in the Liascript Markdown Format

Could you please write the "________" section using Markdown. Please include the "_____" and "_______" subsections. Explain the concept, include examples of errors students make and 3 quiz questions in the markdown format.
