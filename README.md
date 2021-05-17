Design a Web page for users for renting the books as given below :





Use HTML Table to align the form elements

·       Display text "Rent Books" in a span element by applying the style

Put the text  in a h2 tag by applying the style (background color with #000080 and text color with #ff6600)


Create a form which accepts below fields

·        Book Name (Drop Down)

·        User Name  

·        Rent Start Date

·        Rent Tenure

·        Number of Books available
Validations

·        “User Name” is input text box, should be minimum of 5 characters and should take only characters and space (Use OnBlur event)

·        Enter number of books (Number)

·        Submit button with text “Submit Query”






·        “Rent Start Date” is input date field, and the date selected should be current or future date

·        “Rent Tenure” is number field should not accept more than 30, when entered more than 30 display a text “We cannot rent over 30 days SORRY!!!”

·        “Number of Books available” (to be hardcoded in JavaScript function which will be called at onLoad event, for all the book the max value available is 5)

⦁ “Rent Books” input text box should not be more than the value specified in the “Number of Books available”



Additional Note:

·        Load few books in the field Book Name (Drop Down), namely [HTML, DBMS, SE, JAVA, PYTHON, ML, ]

·        When User clicks on submit, do the following checks

        i.  Show the total Rental cost which is cost of the book(s) and number of days the book is opted for ex: 100 (cost per day) x Qty x 8 days = 800. When user clicks on confirm box as “Yes”, then a message to be shown “Thank you for order Mr/Ms/Mrs: <Customer Name>” 
