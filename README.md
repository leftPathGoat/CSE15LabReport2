# CSE15LabReport2
**StringServer(URL Handler and Server)** 

![Image](URLhandler.jpg)

![Image](Screenshot 2023-04-23 232303.jpg)

**Calling add on server**
Simply change the url and add `/add-message?s=note` change note to your custom message

![Image](hello.jpg)

The method handleRequest from class URLHandler were called by the main method in StringServer. The relevent argument was the URL input to handleRequest method.
The url request was analyzed and the query message stored in field stList. The message "hello" was added to field result.
The field stList chaned from an empty arrayList to an arrayList with a single element. The field result changed from an empty array to "hello".

![Image](Screenshot 2023-04-23 233457.jpg)

The method handleRequest from class URLHandler were called by the main method in StringServer. The relevent argument was the URL input to handleRequest method.
The url request was analyzed and the query message stored in field stList. The message "Welcome to Francis' Server" was added to field result.
The field stList chaned from an empty arrayList to an arrayList with a single element. The field result changed from an empty array to "hello\nWelcome to Francis' Server".

**Step 3:** Open terminal in VScode -> view -> terminal

![Image](terminal.jpg)
